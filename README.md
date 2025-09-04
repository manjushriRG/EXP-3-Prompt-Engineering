# EXP-3-PROMPT-ENGINEERING-

## Aim: 
Evaluation of 2024 Prompting Tools Across Diverse AI Platforms: 
ChatGPT, Claude, Bard, Cohere Command, and Meta
Experiment:
Within a specific use case (e.g., summarizing text, answering technical questions), compare the performance, user experience, and response quality of prompting tools across these different AI platforms.

## Algorithm:
**Define scope & dataset:**.<br>
Use Cases: Summarization, Technical Question Answering.<br>
Prompts: Created for both simple and complex scenarios.

**Define evaluation rubric:**.<br>
Metrics: Accuracy, Relevance, Clarity, Completeness/Depth, Conciseness, Safety (No hallucination)..<br>
Scale: 1–5 per metric.

**Generate outputs:**.<br>
For each platform, issue the same prompt.<br>
Collect outputs along with metadata (time, version, parameters).

**Evaluation:**.<br>
Blind evaluation (platform name hidden).<br>
Human raters scored each output.

**Aggregate scores:**.<br>
Mean metric per platform.<br>
Overall composite scores computed.

**Statistical & qualitative analysis:**.<br>
Identify significant differences across platforms.<br>
Note behavioral patterns (verbosity, oversimplification, formal tone).

**Reporting:**.<br>
Present outputs in Prompt → Output → Result format.<br>
Provide comparative tables and rankings.

## Experiment and Results:
## Case 1: Summarizing Text

## Prompt:
“Summarize the following text into three sentences:
Artificial intelligence is rapidly evolving and is transforming industries such as healthcare, education, and finance. However, ethical challenges related to privacy, fairness, and accountability remain critical. Governments, researchers, and companies are working together to ensure responsible deployment of AI.”

## ChatGPT Output:
Artificial intelligence is revolutionizing industries like healthcare, education, and finance. Ethical issues such as privacy, fairness, and accountability remain central challenges. Governments, researchers, and companies are collaborating for responsible AI deployment.
Result: Accuracy ✅ | Clarity ✅ | Conciseness ✅ | Overall: Excellent

## Claude Output:
AI is transforming sectors like healthcare, finance, and education at a rapid pace. This expansion raises ethical issues around privacy, fairness, and accountability. Governments and industries are cooperating to ensure responsible AI.
Result: Accuracy ✅ | Clarity ✅ | Style: Polished | Overall: Very Good

## Bard/Gemini Output:
AI is changing industries but creates challenges like fairness and privacy. Governments and companies are finding solutions. The aim is to ensure responsible AI for society.
Result: Accurate but oversimplified | Clarity ✅ | Overall: Moderate

## Cohere Command Output:
AI is spreading across finance, education, and healthcare. Ethical concerns—privacy, fairness, and accountability—affect adoption. Governments and companies are acting to build trust in AI.
Result: Accurate | Technical tone | Overall: Good

## Meta AI Output:
AI affects finance, healthcare, and education. Challenges include privacy and accountability. Governments and researchers work for safe AI.
Result: Factual but fragmented | Overall: Average

## Case 2: Technical Question Answering

## Prompt:
“What is the role of power electronics in Vehicle-to-Grid (V2G) systems?”

## ChatGPT Output:
Power electronics enable bidirectional energy flow between EV batteries and the grid. They manage charging and discharging while ensuring voltage regulation, safety, and grid stability.
Result: Detailed | Accurate | Clear | Excellent

## Claude Output:
In V2G, power electronics control energy exchange between the grid and EV batteries. They enable charging/discharging and maintain safety and efficiency.
Result: Concise & Correct | Very Good

## Bard/Gemini Output:
Power electronics let vehicles charge and discharge power safely. This balances the grid.
Result: Too simple | Lacks depth | Fair

## Cohere Command Output:
Power electronics are the backbone of V2G, providing DC–AC conversion, switching, and protection. They ensure EVs act as reliable grid resources.
Result: Technically strong | Slight jargon | Good

## Meta AI Output:
V2G uses power electronics for charging, discharging, and conversion between vehicles and the grid.
Result: Minimal explanation | Average

## Case 3: Summarizing Renewable Energy Text

## Prompt:
“Summarize the following passage into a short paragraph:
Renewable energy sources, such as solar, wind, and hydropower, are increasingly adopted to reduce dependence on fossil fuels. These energy systems are environmentally friendly, sustainable, and help in reducing carbon emissions. However, challenges remain in terms of energy storage, grid integration, and cost competitiveness.”

## ChatGPT Output:
Renewable sources like solar, wind, and hydropower reduce reliance on fossil fuels and cut carbon emissions. They are eco-friendly and sustainable but face challenges of storage, grid integration, and costs.
Result: Balanced, accurate, concise | Excellent

## Claude Output:
Solar, wind, and hydropower are growing as sustainable energy options that lower fossil fuel use and emissions. Despite their benefits, challenges with storage, integration, and affordability remain.
Result: Clear, professional tone | Very Good

## Bard/Gemini Output:
Renewables like solar, wind, and hydropower cut emissions and replace fossil fuels. They are sustainable but struggle with storage, integration, and costs.
Result: Concise, beginner-friendly | Good

## Cohere Command Output:
Renewable energy, including solar, wind, and hydropower, offers sustainable, low-carbon alternatives to fossil fuels. But growth is limited by storage, integration, and cost barriers.
Result: Technical, structured | Very Good

## Meta AI Output:
Solar, wind, and hydropower help reduce fossil fuel use but face storage, grid, and cost issues.
Result: Factual but shallow | Average
## Comparative Analysis:
| Platform        | Accuracy  | Clarity   | Depth       | Conciseness | UX                | Overall Rank |
| --------------- | --------- | --------- | ----------- | ----------- | ----------------- | ------------ |
| **ChatGPT**     | Excellent | Excellent | High        | Balanced    | Smooth            | ⭐ #1         |
| **Claude**      | Very Good | Excellent | Medium-High | Polished    | Clean             | ⭐ #2         |
| **Cohere**      | Good      | Good      | Medium      | Technical   | Enterprise feel   | ⭐ #3         |
| **Bard/Gemini** | Moderate  | Good      | Low         | Strong      | Beginner-friendly | ⭐ #4         |
| **Meta AI**     | Average   | Fair      | Low         | Simple      | Basic             | ⭐ #5         |
## Observations:
**ChatGPT:** Best balance of depth, accuracy, and adaptability; suited for students, researchers, and professionals.<br>
**Claude:** Excellent clarity and ethical phrasing; slightly less detailed.<br>
**Cohere Command:** Technically robust, enterprise-focused tone; less conversational.<br>
**Bard/Gemini:** Highly concise and simple; best for beginners, not experts.<br>
**Meta:** Functional but minimal depth, often oversimplified.<br>
## Conclusion:
ChatGPT ranked the highest overall, followed closely by Claude. Cohere Command performed strongly in technical depth but felt formal. Bard/Gemini excelled in conciseness but lacked detail. Meta was clear but shallow.<br>
**Final Ranking:**
1. ⭐ ChatGPT

2. ⭐ Claude

3. ⭐ Cohere Command

4. ⭐ Bard/Gemini

5. ⭐ Meta

