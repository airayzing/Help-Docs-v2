---
description: 'Here is a structured guide on Chat Components under "Request Information":'
---

# 📖 Request Information

Here’s a structured breakdown of the available **chat components** and their use cases:

#### **Basic Input Components**

1. **Name**
   * Requests the user's name.
   * Customize the request message in the **Customize Bot Message** section.
2. **Phone Number**
   * Requests the user’s phone number.
   * Allows selecting a **specific country code** from a dropdown.
3. **Email**
   * Requests the user's email address.
   * The message can be customized in the **Customize** panel.

#### **Choice-Based Components**

4. **Single Choice**
   * Allows users to select **one** option from a list (up to 5 options).
   * Each option can be linked to the next component.
5. **Multiple Choice**
   * Enables users to select **multiple** options (up to 5).
   * Each option can be connected to a subsequent action.

#### **User Input & File Upload**

6. **Text Question**
   * Requests an **open-ended response** from the user.
7. **File Upload**
   * Allows users to upload a **file, image, or video**.
   * Customize the request message in the left panel.

#### **Advanced Interactive Components**

8. **iFrame**
   * Embeds an **external webpage** into the chat.
   * Requires a **URL, title, and CTA button**.
9. **Appointment**
   * Lets users book an appointment.
   * Set **availability hours, time slot intervals, and future booking days**.
   * Integrate with a third-party scheduling tool.
10. **Location**

* Requests a **text-based location** from the user.

11. **Date/Time Picker**

* Collects **date and time** inputs.
* Offers a calendar-based selection for users.

#### **Feedback & Numeric Inputs**

12. **Rating**

* Collects user ratings and feedback.
* Supports **5 rating options**.

13. **Range Selector**

* Allows users to input a value within a **specified range**.
* Supports custom **prefix, suffix, and step values**.

14. **Numeric Input**

* Accepts **only numerical values** as input.

#### **Dynamic & Logic-Based Components**

15. **Smart Question**

* Directs the conversation based on user responses.
* Supports **keyword-based routing** (exact match or keyword presence).

16. **Redirect**

* Connects to another **pre-built chat flow**.
* The conversation seamlessly continues in the selected flow.

#### **API & Integrations**

17. **API Component**

* Integrates a **third-party service** into the chat flow.
* Handles **response codes** (200 = success, 400 = error).
* More details available in the **Developers** section.

Each of these components plays a crucial role in enhancing chatbot flexibility, enabling **seamless conversations, user interactions, and third-party integrations**. 🚀
