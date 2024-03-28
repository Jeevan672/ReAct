# ReAct


ReAct is a prompting strategy that combines CoT reasoning with action planning.
ReAct structures prompts to include a sequence of one or more question, thought,
action, and observation examples as described in the ReAct paper https://arxiv.org/pdf/2210.03629.pdf

The question is the user-requested task or problem to solve. The thought is a reason‐
ing step that helps demonstrate to the foundation model how to tackle the problem
and identify an action to take. The action is an API that the model can invoke from
an allowed set of APIs. The observation is the result of carrying out the action. The
actions that the model is able to choose from are defined by a set of instructions that
are prepended to the example prompt text.

Let’s return to the generative AI-based travel application example and assume a
user is asking which hotel is closest to the most popular beach in Goa. This
question will take a couple of intermediate steps and actions to find the solution.
In the prompt-prepended instructions, describe the ReAct prompt structure and list
the allowed actions.

Let’s give the agent API access to a Google search
