# Handwriting Transfer

This repository will contain codes and notes for a project I am working on. The goal is to create a model that can transfer handwriting. The specific detail on how to do this will be decided later.

## What is the goal in a vague sense?

The goal is to create a model that can transfer handwriting. The final product, if I am able to make it, will take an image from a user with something written in the current and target handwriting and will convert the texts of the current handwritten text to the target handwriting.

## How to do this?

There are a number of approaches. Some of them are:

1. Treat this as a two-step process: The first step is a simple OCR and the second step will be to extract features from the handwriting and then write the OCRed text.
2. Use GAN to transfer the handwriting style from the current to the target.