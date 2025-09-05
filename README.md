
---

# EXPERIMENT – 3: Scenario-Based Report Development Using Diverse Prompting Approaches

### Register No.: 212223060284

### Date: 05.09.2025

---

## Aim:

To design an AI-powered customer service chatbot that can efficiently address **product troubleshooting, order tracking, and general queries** using **Straightforward Prompting, Tabular Format Prompting, and Preceding Question Prompting**.

---

## Tools Required:

* AI platforms (ChatGPT, Gemini, Claude)
* Word/Excel (for organizing results)
* Internet connection
* Screenshots of chatbot conversations

---

## Theory:

Prompt engineering refers to designing instructions (prompts) in a structured way to make AI generate the desired output. Different prompt types influence how information is displayed:

| **Prompting Type**           | **Description**                                                      | **Best For**                        |
| ---------------------------- | -------------------------------------------------------------------- | ----------------------------------- |
| Straightforward Prompting    | Direct question or instruction to get a simple, precise answer.      | Quick facts, direct queries.        |
| Tabular Prompting            | AI is instructed to present output in table form.                    | Comparisons, troubleshooting steps. |
| Preceding Question Prompting | Builds conversation step by step, using previous answers as context. | Natural, human-like interactions.   |

---

## Experiment Procedure:

We tested **three scenarios** with all three prompting techniques.

---

### 📌 Scenario 1: Product Troubleshooting

| **Prompt Type**              | **Example Prompt**                                               | **Generated Response** (Shortened)                                      |
| ---------------------------- | ---------------------------------------------------------------- | ----------------------------------------------------------------------- |
| Straightforward Prompting    | “Why is my smart vacuum cleaner not charging?”                   | *Check power supply → Clean charging pins → Replace battery.*           |
| Tabular Format Prompting     | “Give causes and solutions for vacuum not charging in a table.”  | (See table below)                                                       |
| Preceding Question Prompting | Q1: “My vacuum isn’t charging.” <br> Q2: “It shows a red light.” | *AI: Red blinking = Battery overheating. Suggest cooling before retry.* |

**Troubleshooting Table Output (from Tabular Prompting):**

| **Cause**                   | **Solution**              |
| --------------------------- | ------------------------- |
| Power adapter faulty        | Test/replace adapter.     |
| Dust blocking charging port | Clean with dry cloth.     |
| Battery overheated          | Allow device to cool.     |
| Internal battery failure    | Replace with new battery. |


---

### 📌 Scenario 2: Order Tracking

| **Prompt Type**              | **Example Prompt**                                        | **Generated Response**               |
| ---------------------------- | --------------------------------------------------------- | ------------------------------------ |
| Straightforward Prompting    | “Track order #24567 placed on 1st September.”             | *Order shipped, arriving by Sept 7.* |
| Tabular Format Prompting     | “Show order #24567 delivery stages in table format.”      | (See table below)                    |
| Preceding Question Prompting | Q1: “Track order #24567.” <br> Q2: “When will it arrive?” | *AI: Expected delivery Sept 7.*      |

**Order Tracking Table Output (from Tabular Prompting):**

| **Stage**        | **Status**         | **Date**    |
| ---------------- | ------------------ | ----------- |
| Ordered          | Confirmed          | 01-Sep-2025 |
| Packed           | Ready for dispatch | 02-Sep-2025 |
| Shipped          | In Transit         | 03-Sep-2025 |
| Out for Delivery | Expected tomorrow  | 06-Sep-2025 |


---

### 📌 Scenario 3: General Inquiry

| **Prompt Type**              | **Example Prompt**                                                      | **Generated Response**                       |
| ---------------------------- | ----------------------------------------------------------------------- | -------------------------------------------- |
| Straightforward Prompting    | “What is your customer service helpline number?”                        | *Helpline: 1800-123-456 (Mon–Sat, 9AM–6PM).* |
| Tabular Format Prompting     | “Provide customer support channels in a table.”                         | (See table below)                            |
| Preceding Question Prompting | Q1: “Do you have weekend support?” <br> Q2: “How to contact on Sunday?” | *Email only, no phone support on Sunday.*    |

**Support Information Table Output (from Tabular Prompting):**

| **Channel**    | **Contact Details**                               | **Availability**      |
| -------------- | ------------------------------------------------- | --------------------- |
| Phone Helpline | 1800-123-456                                      | Mon–Sat, 9 AM – 6 PM  |
| Email Support  | [support@company.com](mailto:support@company.com) | 24/7                  |
| Live Chat      | Via Mobile App/Website                            | Mon–Fri, 10 AM – 8 PM |

---

## Evaluation & Observations:

* Straightforward Prompts → Worked best for **simple queries** like helpline numbers.
* Tabular Prompts → Excellent for **step-by-step troubleshooting** and structured info.
* Preceding Question Prompts → Created the most **realistic, engaging conversation flow**.

---

## Conclusion:

Different prompting techniques significantly influenced the chatbot’s effectiveness.

* **Straightforward Prompting** → Quick and direct responses.
* **Tabular Prompting** → Organized and detailed outputs.
* **Preceding Question Prompting** → Human-like conversational flow.

Hence, the chatbot successfully handled **troubleshooting, order tracking, and general inquiries** using all three prompting methods.

---

## Result:

The experiment was successfully performed. The chatbot demonstrated the ability to resolve diverse customer queries effectively by applying multiple prompting strategies.

