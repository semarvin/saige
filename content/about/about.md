+++
author = "S. E. Marvin"
title = "About"
date = "2021-03-13"
description = "What is SAIGE?"
categories = ["About Saige"]
+++

SAIGE is a model of GPT-2 trained on a corpus of Surrealist literature, essays, and poetry. SAIGE was created using Python 3.6. I worked with the 124 M model of GPT-2, the smallest model, due to limitations on computing power and storage. I trained GPT-2 on my corpus for about fifty hours, generating over 7300 steps, leaving SAIGE well-versed on the Surrealist corpus I had assembled. 

After finishing SAIGE’s training, I could generate samples of its own writing. I initially generated eight samples at three different temperatures, but later generated between eight and sixteen more at each temperature to better understand SAIGE’s abilities. Temperature controls the amount of entropy in the text. Generating samples at low temperatures instructs SAIGE to choose the most likely combination of words based on its training data; conversely, then, using higher temperatures increases the amount of randomness in SAIGE’s word selection. Usually, temperature values are between 1 and 0, so I generated samples at temperatures of 0.2, 0.5, and 0.8 in order to understand SAIGE’s full range of textual generation. Each sample generated was about 800 words long, though some were much shorter and some were much longer. SAIGE generated unconditional samples in order to evaluate SAIGE’s text without my prompting. 