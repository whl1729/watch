# ChatGPT Prompt Engineering for Developers 课程笔记

## Content

- 01 Intro
- 02 Guidelines
- 03 Iterative
- 04 Summarizing
- 05 Inferring
- 06 Transforming
- 07 Expanding
- 08 Chatbot
- 09 Conclusion

## 01 Intro

- Two Types of LLMs
  - Base LLM
  - Instruction Tuned LLM
    - Fine-tune on instructions and good attempts at following those instructions
    - RLHF: Reinforcement Learning with Human Feedback

## 02 Guidelines

- Principles of Prompting
  - Principle 1: Write clear and specific instructions (clear != short)
  - Principle 2: Give the model time to think

- Model Limitations
  - Hallucination
  - Reducing hallucinations
    - First find relevant information
    - then answer the question based on the relevant information

### Principle 1

- Tactic 1: Use delimiters
  - Avoiding Prompt Injections

  ```text
  Triple quotes: """
  Triple backticks: ```
  Triple dashes: ---
  Angle brackets: <>
  XML tags: <tag> </tag>
  ```

- Tactic 2: Ask for structured output
  - HTML, JSON
  - 针对输出的各部分内容分别提出格式要求

> 伍注：可以用来生成一些测试用例。

- Tactic 3: Check whether conditions are satisfied. Check assumptions required to do the task

- Tactic 4: Few-shot prompting
  - Give successful examples of completing tasks
  - Then ask model to perform the task

### Principle 2

- Tactic 1: Specify the steps to complete a task

- Tactic 2: Instruct the model to work out its own solution before rushing to a conclusion

## 03 Iterative

- Iterative Prompt Development
  - Idea
  - Implementation (code/data)
  - Experimental result
  - Error Analysis

- Prompt guidelines
  - Be clear and specific
  - Analyze why result does not give desired output
  - Refine the idea and the prompt
  - Repeat

- Iterative Process
  - Try something
  - Analyze where the result does not given what you want
  - Clarify instructions, give more time to think
  - Refine prompts with a batch of examples

## 04 Summarizing

## 05 Inferring

## 06 Transforming

- 翻译
- 识别文本对应的语言
- 写信、写通知、写邮件等
- 格式转换
- 纠正文本错误

> 伍注：发表文章前可以用 ChatGPT 检查错误。

## 07 Expanding

- Temperature

## 08 Chatbot

- Role
  - system: Sets behavior of assistant
  - assistant: Chat model
  - user: You

## 09 Conclusion
