## LM as Dynamical System

Workflow:

- Generate large output from a small Language model like GPT2, which potentially repeats itself.
- Get the embedding of the text output.
- Find the principal component. This will give us a time series.
- Use delay coordinate embedding to potentially reconstruct the attractor.
- Find the differential equation responsible for that attractor.
