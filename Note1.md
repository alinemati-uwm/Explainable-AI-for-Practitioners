# What Is Explainable AI?

At Explainable AI’s core is the creation of explanations, or to create explainability for a model. Explainability is the concept that a model’s actions can be described in terms that are comprehensible to whoever is consuming the predictions of the ML model. This explainability serves a variety of purposes, from improving model quality to building confidence, and even providing a pathway for remediation when a prediction is not one you were expecting. As we have built increasingly complex models, we have discovered that a high-performing model is not sufficient to be acceptable in the real world. It is necessary that a prediction also has a reasonable explanation and, overall, the model behaves in the way its creators intended.

# Challenges in Explainability

In Explainable AI, there are several outstanding challenges:

- Demonstrating the semantic correctness of explanation techniques above and beyond the theoretical soundness of the underlying mathematics

- Combining different explanation techniques in an easy and safe way that enhances understanding rather than generating more confusion

- Building tools that allow consumers to easily explore, probe, and build richer explanations

- Generating explanations that are computationally efficient

- Building a strong framework for determining the robustness of explanation techniques

# What Are Explanations?


When a model makes a prediction, Explainable AI (XAI) methods generate an explanation that gives insight into the model’s behavior as to how it arrived at that prediction. When we seek explanations, we are trying to understand, Why did X happen? As an example, if we had a weather model that predicted when it rains, and we wanted to know why the model suddenly gave a 90% chance of precipitation, a useful explanation would be, 90% precipitation was predicted because the sky was overcast. Figuring out this why can help us build a better comprehension of what influences a model, how that influence occurs, and where the model performs (or fails). As part of building our own mental models, we often find a pure explanation to be unsatisfactory, so we are also interested in explanations that provide a counterfactual, or foil, to the original situation. Counterfactuals are scenarios that seek to provide an opposing, plausible, scenario of why X did not happen. If we are seeking to explain, Why did it rain today? we may also try to find the counterfactual explanation for, Why did it not rain today [in a hypothetical world]? While our primary explanation for why it rained might include temperature, barometric pressure, and humidity, it may be easier to explain that it did not rain because there were no clouds in the sky, implying that clouds are part of an explanation for why it does rain.

