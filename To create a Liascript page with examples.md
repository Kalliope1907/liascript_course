To create a Liascript page with examples for multiple choice, you can follow these steps:

1. Start by creating a new file with the `.lia` extension, for example, `multiple_choice.lia`.

2. Begin the file by adding the necessary Liascript metadata. Here's an example:

```
title: Multiple Choice Examples
author: Your Name
description: Examples of multiple choice questions using Liascript
```

3. Next, you can start adding your multiple choice questions. Use the `mc` tag to define a multiple choice question and its options. Here's an example:

```
mc: What is the capital of France?
- Paris
- London
- Berlin
- Rome
```

4. You can add as many multiple choice questions as you need, each with its own set of options.

5. To display the correct answer(s) for each question, use the `correct` tag followed by the index(es) of the correct option(s). For example:

```
mc: What is the capital of France?
- Paris
- London
- Berlin
- Rome
correct: 1
```

6. You can also add explanations for the correct answers using the `explanation` tag. For example:

```
mc: What is the capital of France?
- Paris
- London
- Berlin
- Rome
correct: 1
explanation: Paris is the capital of France.
```

7. Once you have added all your multiple choice questions, you can save the file and open it in a Liascript viewer to see the rendered output.

Remember to use proper Markdown syntax within the Liascript file to format your content as needed.
