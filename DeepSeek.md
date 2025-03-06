# Q1 How Deepseek is differ from chatgpt.

Ans: Deepseek uses MOE(Mixture of Experts) architecture by which they reduce the computational cost .

MOE activates the subset of Parameters for Each Query.
While chatgpt activates all parameters for the Each Query.

They have 671 billion total parameters, DeepSeek activates just 37 billion per query.

For Example : If i give a query like what is AI ,deepseek just activates the 37 billion parameters while chatgpt activates the all the parameters for this query.

Deepseek R1 Model is Specialized for reasoning tasks , maths Problem while Deepseek V3 is mostly a general purpose model with multimodal capabilities like image processing ,document processing and text.

Deepseek uses attention mechanism By which it remembers the context between the sentences.

After Initial training , deepseek uses reinforcement learning with human feedback,human checks the model response

For example : I ask a question what is the capital of india ,the model generates the response the human will rank the response which response is better and which is not.