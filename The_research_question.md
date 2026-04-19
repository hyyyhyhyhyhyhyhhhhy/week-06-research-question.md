The space that the research questions are regarding to: The Scene Describer 
The observation: Different language models vary in how effectively they follow structured prompts to produce detailed and viewpoint-consistent scene descriptions. 

ChatGPT's response after inputting the following prompt: 
I'm a high school student in an applied AI course. I'm interested in AI rethinking the angle of a photo. I want to write a short research brief on this but I don't have a research question yet — I just have the observation: Different language models vary in how effectively they follow structured prompts to produce detailed and viewpoint-consistent scene descriptions. Can you help me sharpen this into a researchable question? Don't give me the answer. Give me three candidate questions at different levels of specificity, and explain what would count as evidence for each one. 

The Response 1: 
1) Broad (comparative capability question)

Research question:
How do different language models vary in their ability to generate coherent, structured scene descriptions from the same visual input?

What this is really testing:
General differences in instruction-following and descriptive quality across models.

What counts as evidence:

Side-by-side outputs from multiple models given identical image + prompt
Human or rubric-based scoring of:
coherence (does the description make sense overall?)
structure adherence (does it follow the requested format?)
completeness (does it capture key elements of the scene?)
Statistical comparison of scores across models (even simple averages would work for a school-level study)
2) Mid-level (your “angle change” idea becomes explicit)

Research question:
How effectively do different language models maintain viewpoint consistency when asked to describe the same image from a specified camera angle or perspective?

What this is really testing:
Whether models can transform perspective mentally (e.g., “describe this scene as if viewed from above / behind the subject / from the left side”).

What counts as evidence:

Same image, multiple prompts with different requested viewpoints
Evaluation of:
viewpoint consistency (does the description actually reflect the requested angle?)
spatial plausibility (do object positions make sense from that angle?)
A scoring rubric like:
0 = ignores viewpoint
1 = partially follows viewpoint
2 = fully consistent viewpoint transformation
You could also include disagreement cases as qualitative evidence (where models “hallucinate” impossible perspectives)
3) Narrow + strongest (focused on prompt structure + reasoning)

Research question:
How does prompt structure (e.g., explicit step-by-step constraints vs. free-form instructions) affect a language model’s ability to generate viewpoint-consistent scene reconstructions from images?

What this is really testing:
Interaction between prompt engineering and spatial reasoning under constraints. 

What counts as evidence:

Same model, same image, but different prompt formats:
Free-form: “Describe this image from the left side.”
Structured: “Step 1: identify objects → Step 2: reposition from left viewpoint → Step 3: describe final scene”
Compare outputs using:
consistency with requested viewpoint
structural adherence (did it follow the steps?)
reduction in contradictions or spatial errors
You could even quantify “improvement due to structure” as a percentage difference in rubric scores

The response 2: 
1) Broad

Research question:
How well do different language models preserve spatial relationships when generating descriptions of visual scenes?

What counts as evidence:

Give models the same image and ask for descriptions
Check whether relationships stay consistent:
“left/right,” “in front of/behind,” “above/below”
Evidence comes from:
annotated errors in spatial relationships
comparison of accuracy scores across models
frequency of contradictions (e.g., object swaps position incorrectly)
2) Mid-level

Research question:
How accurately do language models maintain spatial relationships when asked to describe a scene from a transformed viewpoint (e.g., rotated or reversed perspective)?

What counts as evidence:

Same image, but prompts like:
“Imagine the camera rotates 90° clockwise”
“Describe the scene from behind the main subject”
Evaluation:
consistency of object placement after transformation
whether relative positions remain logically correct under the new viewpoint
You could measure:
% of correct spatial transformations
number of logical inconsistencies introduced after “rotation”
3) Specific

Research question:
Does explicitly instructing a language model to mentally “rotate” a scene step-by-step improve its accuracy in generating viewpoint-consistent descriptions compared to direct re-description prompts?

What counts as evidence:

Two prompt conditions:
Direct: “Describe this image from the left side.”
Structured transformation: “Step 1: identify objects → Step 2: mentally rotate scene → Step 3: describe from left view”
Compare outputs using:
spatial accuracy rubric (correct/incorrect placement)
number of hallucinated objects introduced during transformation
consistency across multiple runs (stability of output)
Evidence is strongest if structured prompting consistently reduces spatial errors 

The response 3: 
1) Broad

Research question:
How do different language models vary in their ability to reinterpret a visual scene from alternative perspectives?

What counts as evidence:

Same image, multiple models
Prompts like “describe this scene from a different perspective”
Evidence includes:
variety and plausibility of reinterpretations
whether models go beyond literal description
comparison of creativity vs fidelity to original image
You’d likely classify outputs into categories like:
literal description
partially reimagined perspective
fully transformed perspective
2) Mid-level

Research question:
How effectively do language models generate consistent alternative viewpoints (e.g., first-person vs third-person vs aerial) of the same visual scene?

What counts as evidence:

Same image, multiple specified perspectives:
“first-person view of a person in the scene”
“bird’s-eye view”
“side view from left”
Evidence focuses on:
internal consistency within each viewpoint (does it stay coherent?)
whether each viewpoint is meaningfully distinct from others
spatial plausibility of the imagined camera position
You could measure:
distinctiveness score between viewpoints
consistency score within each viewpoint
3) Specific

Research question:
Does explicitly assigning a role (e.g., “you are a drone camera” or “you are a person inside the scene”) improve a language model’s ability to generate coherent and distinct viewpoint-based descriptions compared to neutral prompts?

What counts as evidence:

Two prompt conditions:
Neutral: “Describe this image from above.”
Role-based: “You are a drone flying above the scene. Describe what you see.”
Compare outputs using:
clarity of viewpoint anchoring (is the perspective stable and consistent?)
level of spatial detail (does it improve or degrade?)
distinctiveness between roles (drone vs human vs side observer)
Strong evidence would show that role assignment leads to:
more stable viewpoint reasoning
fewer contradictory spatial descriptions
clearer “camera logic” in the text 

The paragraph: 
I would like to pursue the question "How well do different language models preserve spatial relationships when generating descriptions of visual scenes?". The reason is that in the last week's experiments, both of the 2 models being tested had some issues with the spatial depth thinking, so I would like to find out what is going on. For me, success would look like for different language models, different and matching results occurs and I can tell if that's what's supposed to happen with the model used. 
