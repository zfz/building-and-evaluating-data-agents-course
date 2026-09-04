# Quiz

**Result:** Pass · 7/7 points earned (pass threshold: 5/7)

Last submitted on Sep 04, 2026 04:45 PM (UTC-4)

---

### Question 1
**You are building your first data agent for a collaborator. They ask, "What exactly is a data agent?" How would you explain it to them?**

- A data agent is primarily a visualization tool that creates charts from pre-existing reports.
- A data agent is a scheduled batch processing system that generates reports from databases on a fixed timeline.
- ✅ A data agent is an autonomous system powered by large language models that connects to data sources to answer complex queries. (correct)
- A data agent is a manual workflow managed by data analysts who query databases on behalf of users.

> Data agents use LLMs to autonomously connect to various data sources, interpret queries, and return insights.

### Question 2
**Your team debates whether to use one general-purpose agent or multiple special-purpose agents. Why do specialized agents often produce better results?**

- Specific agents with limited tools capture less context to help reduce latency.
- Specific agents share standard prompts and tools to streamline coordination.
- Specific agents with expanded context windows expose more information for better decisions.
- ✅ Specific agents with dedicated tools and prompts reduce hallucinations and context overload. (correct)

> Focused agents with tailored tools and prompts avoid off-task behavior and context bloat, yielding consistent results.

### Question 3
**Which statement correctly describes the four evaluation dimensions of the GPA framework?**

- ✅ Plan quality: achieves the goal; Plan adherence: actions follow plan; Execution efficiency: optimal actions; Logical consistency: no contradictions. (correct)
- Plan quality: level of detail; Plan adherence: timeline met; Execution efficiency: speed; Logical consistency: factual accuracy.
- Plan quality: resource usage; Plan adherence: timeline alignment; Execution efficiency: creativity; Logical consistency: data completeness.
- Plan quality: user satisfaction; Plan adherence: output matching; Execution efficiency: cost; Logical consistency: rule compliance.

> These four dimensions comprehensively evaluate whether an agent accomplishes its goal reliably and efficiently.

### Question 4
**You are implementing evaluations for your data agent. When should you use inline evaluations vs offline evaluations?**

- Use inline evaluations after execution completes; use offline evaluations for real-time monitoring.
- ✅ Use inline evaluations for real-time feedback during execution; use offline evaluations for post-run analysis and improvements. (correct)
- Use inline evaluations to compare multiple agents; use offline evaluations to check plan adherence.
- Use inline evaluations for historical analysis; use offline evaluations for immediate corrections.

> Inline evaluations guide agents during execution, while offline evaluations analyze completed runs for future enhancements.

### Question 5
**You learned to combine CRM data with meeting transcripts. What is an advantage of this approach?**

- It converts qualitative notes into numeric tags for faster dashboard generation.
- It normalizes diverse inputs into a uniform schema for consistent reporting.
- It caches results from multiple systems to reduce query latency.
- ✅ It enables cross-validated insights by joining quantitative CRM metrics with qualitative meeting notes. (correct)

> Combining numeric deal signals with narrative context allows corroboration and richer, actionable insights.

### Question 6
**Your data agent is producing inconsistent results. How does tracing help diagnose the problem?**

- ✅ Tracing captures each agent step, enabling evaluation of performance metrics like relevance and groundedness. (correct)
- Tracing aggregates usage patterns of tokens for capacity planning.
- Tracing compiles periodic summaries for system audits.
- Tracing monitors API interactions to identify network bottlenecks.

> Step-by-step records let you apply evaluation metrics and identify where responses lack relevance or grounding.

### Question 7
**After reviewing metrics indicating low Plan Adherence scores, which improvement strategy would help troubleshoot the issue?**

- Switch to a more powerful language model for better reasoning.
- ✅ Add explicit pre-conditions, post-conditions, and goals to clarify sub-goals and guide execution. (correct)

> These additions help agents understand what each step should achieve, improving plan adherence.
