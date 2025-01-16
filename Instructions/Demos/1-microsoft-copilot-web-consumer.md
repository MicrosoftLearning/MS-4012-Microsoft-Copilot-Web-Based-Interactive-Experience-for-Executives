---
demo:
    title: 'Demo: Microsoft Copilot (consumer/non-m365 account)'
---

[Back to Index](https://microsoftlearning.github.io/MS-4012-Microsoft-Copilot-Web-Based-Interactive-Experience-for-Executives/)

# Microsoft Copilot (copilot.microsoft.com)

## Copilot and Large Language Models

### Talking Points

Microsoft Copilot gives you an AI-powered personal assistant that can answer questions and help with general tasks. I can ask it questions, and it will give me answers similar to what any college-educated person could give.

When you or your organization use Copilot with Commercial Data Protection, your chat is not saved. All data is encrypted, and Microsoft doesn’t retain any of your prompts or responses. They are not used to train the model, so you can be confident that your personal and organizational information is kept confidential.

For example, I can ask a general knowledge question like this and get a lot of great information back. You can think of it as having a basic conceptual model of the world which it can use to answer questions.

**Example:**
- **Prompt:** What can you tell me about elephants?
- **Response:** (Discuss the response)

Copilot uses large language models (LLMs) trained on huge amounts of information, including Bing searches and results. But Copilot isn’t just a fact checker. We can use Copilot as a general reasoning engine that can take your questions and reason on them stochastically. In the industry, we call this inference.

**Example:**
- **Prompt:** I’m more interested in the power of an elephant. How many humans would it take to win a tug-of-war with an elephant? NOTE: Keep in mind the region and your audience as not everyone knows the term "tug-of-war" so you may have to modify accordingly. 
- **Response:** (Discuss the response)

Copilot was able to make assumptions and draw connections between bits of knowledge to give me a more nuanced answer to my question. As we improve Copilot, we’re learning a lot about what these LLMs are good at and what they’re not good at, and we’re building that knowledge into the product as we build it.

### Demo Steps

> **NOTE:** If you want to use your own prompts, start with a topic of general knowledge that’s interesting to you or your customer.

1. To launch Microsoft Copilot, open a new Edge browser tab and navigate to <a href="https://copilot.microsoft.com" target="_blank">copilot.microsoft.com</a>.

1. Sign into a non-work microsoft account.

    > **NOTE:** If you sign into your work account, you will  redirected to Microsoft 365 Copilot Chat (m365.cloud.microsoft/chat) 

1. In the **Message Copilot** text box, copy and paste the prompt from the prompt library documents or type:

    ```text
    What can you tell me about elephants?
    ```
1. Select the **Submit** button.
1. In the **Message Copilot** text box, copy and paste the prompt:

    ```text
    I’m more interested in the power of an elephant. How many humans would it take to win a tug-of-war with an elephant?
    ```
1. Select the **Submit** button.

## Grounding

### Talking Points

But what takes this power to the next level is the ability to ground Copilot in external data and knowledge. Sometimes this is called Retrieval Augmented Generation (RAG). This is the process of providing additional information to the language model that’s relevant to the task at hand.

We can ground our questions in all kinds of data and documents, for example, the Bureau of Labor Statistics jobs report. This is a huge document, published annually, that is full of data about jobs and employment trends across the United States. Copilot is able to go out and find that information, understand it, and give me an answer to my question in real time. It also gives me references that show me where Copilot got that information from, for example, the Bureau of Labor Statistics website. This means I can check where Copilot got its information and get more context, because this is Copilot, not autopilot.

### Demo Steps

1. Start a new topic, by clicking **view history** and then **Start new chat**.

1. In the **Message Copilot** text box, copy and paste the prompt:

    ```text
    Can you give me a list of the labor force participation rates from the Bureau of Labor Statistics over the last 5 years?
    ```
1. Select the **Submit** button.
1. In the response, next to **Learn more**, pause the mouse over one or two of the references.

## Additional Copilot Skills

### Talking Points

This is great, but I’d really like to see a graph of this data. Unfortunately, Copilot can’t draw a graph right now, but that doesn’t mean we’re stuck. As we build Copilot, we’re adding different skills. Skills are ways that Copilot can draw on its reasoning power to solve problems.

Another ability that I know Copilot has is the ability to code. I’m going to remind Copilot that it knows how to code and see if I can get it to write the Python code for that graph I wanted.

**Example:**
- **Prompt:** Can you give me a list of the labor force participation rates from the Bureau of Labor Statistics over the last 5 years? I also heard that you could code. Can you grab the data from bls.gov and then write the Python code that would produce the graph I'm looking for?
- **Response:** (Discuss the response)

Over time, we expect these kinds of processes to become easier and more automated.

### Demo Steps

1. Start a new topic, by clicking **view history** and then **Start new chat**.

1. In the **Message Copilot** text box, copy and paste the prompt:

    ```text
    Can you give me a list of the labor force participation rates from the Bureau of Labor Statistics over the last 5 years? I also heard that you could code. Can you grab the data from bls.gov and then write the Python code that would produce the graph I'm looking for?
    ```

1. Select the **Submit** button.

## Optional Demo Steps

### Recognizing Images

First download the following: [**What is this image.png**](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/raw/master/Resourcefiles/what_is_this_image.PNG)

1. Start a new topic, by clicking **view history** and then **Start new chat**.

1. At the bottum of the page, select the Plus (**+**) icon.

1. Browse to where you downloaded the image, select **What is this picture.png**, and then select **Open**.
1. In the **Message Copilot…** text box type the prompt:

    ```text
    What is this picture?
    ```

1. Select the **Submit** button.

### Show How Copilot Can Create Images

1. In the **Message Copilot** text box, copy and paste the prompt:

    ```text
    Copilot, make a banner for a hamburger stand. Make it friendly and show people enjoying a hamburger.
    ```

1. Select the **Submit** button.

[Back to Index](https://microsoftlearning.github.io/MS-4012-Microsoft-Copilot-Web-Based-Interactive-Experience-for-Executives/)
