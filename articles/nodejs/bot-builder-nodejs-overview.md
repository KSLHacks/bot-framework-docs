---
title: Bot Builder SDK for Node.js | Microsoft Docs
description: Explore the Bot Builder SDK for Node.js, a powerful, easy-to-use bot building framework.
author: DeniseMak
ms.author: v-demak
manager: rstand
ms.topic: article
ms.prod: bot-framework
ms.date: 
ms.reviewer: 
---

# Bot Builder SDK for Node.js

> [!div class="op_single_selector"]
> - [.NET](../dotnet/bot-builder-dotnet-overview.md)
> - [Node.js](../nodejs/bot-builder-nodejs-overview.md)
> - [REST](../rest-api/bot-framework-rest-overview.md)

Bot Builder SDK for Node.js is a powerful, easy-to-use framework that provides a familiar way for Node.js developers to write bots.
You can use it to build a wide variety of conversational user interfaces, from simple prompts to free-form conversations.

The conversational logic for your bot is hosted as a web service. The Bot Builder SDK uses <a href="http://restify.com">restify</a>, a popular framework for building web services, to create the bot's web server. 
The SDK is also compatible with <a href="http://expressjs.com/">Express</a> and the use of other web app frameworks is possible with some adaption. 

Using the SDK, you can take advantage of the following SDK features: 

- Powerful system for building dialogs to encapsulate conversational logic.
- Built-in prompts for simple things such as Yes/No, strings, numbers, and enumerations, as well as support for messages containing images and attachments, and rich cards containing buttons.
- Built-in support for powerful AI frameworks such as <a href="http://luis.ai" target="_blank">LUIS</a>.
- Built-in recognizers and event handlers that guide the user through the conversation, providing help, navigation, clarification, and confirmation as needed.

## Get started

If you are new to writing bots, [create your first bot with Node.js](bot-builder-nodejs-quickstart.md) with step-by-step instructions to help you set up your project, install the SDK, and run your first bot. 

If you are new to the Bot Builder SDK for Node.js, you can start with key concepts that help you understand the major components of the Bot Builder SDK, see [Key concepts](bot-builder-nodejs-concepts.md).

To ensure your bot addresses the top user scenarios, review the [design principles](../bot-design-principles.md) and [explore patterns](../bot-design-pattern-task-automation.md) for guidance.

## Get samples

The [Bot Builder SDK for Node.js samples](bot-builder-nodejs-samples.md) demonstrate task-focused bots that show how to take advantage of features in the Bot Builder SDK for Node.js. You can use the samples to help you quickly get started with building great bots with rich capabilities.

## Additional resources

The following task-focused how-to guides demonstrate various features of the Bot Builder SDK for Node.js.

* [Respond to messages](bot-builder-nodejs-use-default-message-handler.md)
* [Triggering actions](bot-builder-nodejs-global-handlers.md)
* [Recognize user intent](bot-builder-nodejs-recognize-intent.md)
* [Send a rich card](bot-builder-nodejs-send-rich-cards.md)
* [Send attachments](bot-builder-nodejs-send-receive-attachments.md)
* [Saving user data](bot-builder-nodejs-save-user-data.md)


If you encounter problems or have suggestions regarding the Bot Builder SDK for Node.js, 
see [Support](../resources-support.md) for a list of available resources. 


[DesignGuide]: ../bot-design-principles.md 
[DesignPatterns]: ../bot-design-pattern-task-automation.md 
[HowTo]: bot-builder-nodejs-use-default-message-handler.md 
