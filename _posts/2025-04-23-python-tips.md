---
layout: post
title: "Proggramming For Data Science"
date: 2025-4-23
author: "Al Takvir Ahmed Jisan"
categories: [python]
---
here is the 1st code:

import pandas as pd

# Read CSV with specific columns
df = pd.read_csv("data.csv", usecols=['col1', 'col2'])

# Conditional selection
high_scores = df[df['score'] > 80]
