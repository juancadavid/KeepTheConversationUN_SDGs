# KeepTheConversationUN_SDGs
Keep spreading the word on problems and solutions for fulfilling the 17 UN SDG goals. Final project for the Building AI course by Reaktor and University of Helsinki.

## Summary

The United Nations 17 Sustainable Development Goals are the roadmap to save our planet and improve our shared human condition. Unfortunately not many people know about them, and are unaware of the many efforts undergoing at their local and national scale. Let's use the power of AI to keep the conversation on UN SDGs going!

## Background

According to a [World Economic Forum survey](https://www.weforum.org/press/2019/09/global-survey-shows-74-are-aware-of-the-sustainable-development-goals/), three out of four adults worldwide are aware of existence the UN SDGs, but only 6% have manifested to be very familiar with them.
![Global Survey Shows 74% Are Aware of the Sustainable Development Goals](https://assets.weforum.org/editor/large_7RnxWWopV1dhTmULTS3q2Wn1kK6qH2wqHfU8VkeDfMU.PNG)

All around the globe, people, governments and organisations are putting their best efforts to give a better chance for humanity for a dignified life, while preserving our planet's ressources. There are many efforts and initiatives working in the same direction as the UN SDGs without knowing about it.

If we use the power of social networks to keep the conversation going, we will make sure every citizen in the world to be concerned about the small changes they can make to contribute to the UN SDGs.

## How is it used?

The solution is a AI-based conversation monitor that will track conversations on Twitter. Whenever it detects that there is an active and relevant discussion about the problems and solutions related to any of the UN SDGs without explicitly mentioning them, it will classify it as relevant, and a Twitter bot will add a response to the conversation thread encouraging people to discover other relevant conversations related to the same SDG.

The bot will use hashtags for every conversation it has classified as relevant for a particular UN SDG, therefore connecting people among themselves, and adding the official UN link for this SDG, providing with the latest news on the development of this goal.

Example: If a relevant conversation (e.g. more than 5 tweets from different users) deals with the topics of enforced disappearances of human right defenders, the bot will chip in with a tweet stating: "Interesting conversation. Are you aware of the UN SDG #16 'Promote just, peaceful and inclusive societies'? Click [here](https://www.un.org/sustainabledevelopment/peace-justice/) to know more. #UN_SDG16_KeepTheConversation

## Data sources and AI methods
* [Twitter API](https://developer.twitter.com/en/docs)
* Corpus of texts for each of the UN SDGs, available at the [UN Website](https://www.un.org/sustainabledevelopment/peace-justice/)
* NLP, classification
* Transformers

## Challenges

This project will not solve the UN SDGs, but try to help in making them at the center of humanity's endeavours. Also, there are challenges regarding Twitter rules for bots, and avoid being considered a spam bot.

## What next?

It will take time to develop; an infrastructure to host it, and some mastery of the latest state-of-the-art methods for NLP ;)

## Acknowledgments

To everyone working hard to attain the goals; thank you so much!
