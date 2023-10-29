# Emojify

This repository contains my implementation of an emoji classifier using word embeddings. The model is trained on a dataset of text and corresponding emojis.

## Approach

The model consists of a word embedding layer and a feedforward neural network. The word embedding layer converts each word in a sentence into a vector representation. The feedforward neural network then takes these vectors as input and predicts the corresponding emoji.

## Results

The model is highly effective in accurately predicting the corresponding emoji for a given sentence. Here are a few examples:

- "I love you" -> ❤️
- "Congratulations on the promotion!" -> 🍾
- "I'm so happy!" -> 😊

## Usage

To use the model, simply pass a sentence to the model's predict() method. The model will then return the predicted emoji.

You can leverage the model to add emojis to your text messages, enhance your social media posts, or infuse fun and interactivity into your written content. Additionally, consider using it for creating entertaining emoji-based games!

Feel free to clone the repository and experiment with adding emojis to your own text.
