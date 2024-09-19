---
description: >-
  This section contains the FAQs related to the installation of various type of
  bot
---

# Bot Installation FAQs

<details>

<summary>How to install website bot using java script.</summary>

Copy the Javascript code from the WeBots app & Go to y

1. our website's HTML code
2. Paste the script in the head or body tag of your HTML code

**Please Note**

1. Ensure that you paste the script before the tag is closed, i.e., paste the script before `</head>` or `</body>`.
2. Make sure WeBots should be the last script to execute, as some scripts may override the WeBots script.

</details>

<details>

<summary>How to install a bot on a WordPress website?</summary>

After you have logged into your WeBots account, Go to the Bots Tab, select the desired Bot, and navigate to the Install section.

1. Move to the WordPress section and copy the API key available there.
2. Open your website's wp-admin, adding "/wp-admin" at the end of your Domain URL. E.g., If your website URL is "www.expample.com," then you can open WP-Admin using the Link "www.example.com/wp-admin"
3. Go to Plugins > Add new > Search WeBots > Install now > Activate plugin"
4. Install the "WeBots" Plugin and then activate the same.
5. Upon activating the Plugin, you will be redirected to the plugins page with the confirmation message "Plugin Activated."
6. Once your Plugin is activated, paste the Bot Penguin API key in the Box named "WeBots Snippet" that you Copied from your WeBots account.
7. Save the Settings, and you are all set. WeBots has been integrated into your website.

</details>

<details>

<summary>Bot is not showing up upon activation of wp-rocket plugin.</summary>

If you have both wp-rocket and WeBots Plugin/Script added to your WordPress site, You may face the issue of the WeBots not showing up on the website.

In case you are facing such issues, try the below steps, and it will solve the problem.

1. Login to your wp-admin panel and open the `wp-rocket` settings.
2. Go to the `File Optimization` → `JavaScript Files` -> `Load JavaScript deferred`
3. Add the WeBots bot script here under `Exclude Java Script Files` option, and done!

For more details, Check out the following documentation by `wp-rocket`

[https://docs.wp-rocket.me/article/976-exclude-files-from-defer-js](https://docs.wp-rocket.me/article/976-exclude-files-from-defer-js)

</details>

<details>

<summary>What is the minimum browser version requirement for the WeBots website bot?</summary>

WeBots is a JS-based software. Hence your browser must support the Java Script. The minimum requirement for some renowned browsers are as follows:

* Google Chrome: Version 51 or above
* Edge: Version 14 or above
* Safari: Version 10 or above
* Firefox: Version 52 or above

</details>

<details>

<summary>How to resolve the latency issues on my website when I have a chatbot installed?</summary>

We understand the criticality of website speed and responsiveness. Adding a trigger delay only delays the chatbot from opening, but the script of the chatbot is loaded at the same time as the page, which can delay the overall page loading and create latency issues. This happens because of the vast processes that allow chatbots to run smoothly. However, this problem can be solved.

In the document ready function, create a timeout function of 3sec. In that timeout function, create a script element with the details of the script shared while installing the chatbot.

{% code overflow="wrap" lineNumbers="true" %}
```javascript
<script>
    const scriptEle = document.createElement("script");
    scriptEle.src = ('src', 'https://cdn.webots.online/webots.js');
    scriptEle.setAttribute('id', 'webots-messenger-widget');
    scriptEle.innerHTML = '[Your Bot ID]';

    document.onreadystatechange = function () {
      if (document.readyState == "complete") {
        setTimeout(() => {
          document.body.appendChild(scriptEle);
        }, 3000);
      }
    }
  </script>
```
{% endcode %}

**Please note:** Do not forget to replace `[Your Bot ID]` with you bot ID that you can find in your script.

<img src="https://github.com/aiekochat/GitBook-Sync/blob/aman-help-changes/.gitbook/assets/image%20(24).png" alt="" data-size="original">

And done, All sorted.

</details>

<details>

<summary>What are the channels where I can install my bot?</summary>

As of now (13/12/23), We have the following channels where you can run your bot to

1. Website
2. Whatsapp
3. Facebook
4. Telegram
5. Standalone landing page

Also, **Instagram is coming soon!**

</details>
