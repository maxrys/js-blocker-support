
# Advertising text

This extension performs JavaScript blocking on all or on selected domains. Using the "allowed list", the user determines on which domains JavaScript is allowed to run.



## Description

If this Safari extension is enabled for any domains, then by default it blocks JavaScript code on any domains (the recommended mode of operation).

If this Safari extension is enabled for selected domains only, then by default it blocks JavaScript code only on the selected domains.

Using the extension settings, the user can add a domain to the "allowed list". A domain from the "allowed list" can use JavaScript.

When you open an unknown domain, you can be sure that no JavaScript code will be executed on it until you approve it (if you previously selected the recommended operating mode). This ensures that potential miners, keyloggers or any other malicious programs written in JavaScript cannot run unless you approve it. Please note that this extension is not able to determine whether a JavaScript program is malicious.

By default, the following types of JavaScript will be blocked for the current domain:
1) any external JavaScript from the current domain;
2) any external JavaScript from a third party;
3) any embedded JavaScript (can be located directly in the HTML document, in the "script" tags);
4) any inline (events) JavaScript (can be located directly in the HTML document, in attributes with names starting with "on…=…");
5) JavaScript in a frame/iframe, of any of the above types, from any domain.

Once a domain is added to the "allowed list", the following types of JavaScript will be enabled within the current domain:
1) any external JavaScript from the current domain;
2) any external JavaScript from a third party;
3) any embedded JavaScript (can be located directly in the HTML document, in the "script" tags);
4) any inline (events) JavaScript (can be located directly in the HTML document, in attributes with names starting with "on…=…");
5) JavaScript in a frame/iframe, of any of the above types, from any domain.
