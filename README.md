1.	Token count
Sentence: “Artificial intelligence can help people solve problems more efficiently, but in the same time it has a lot of risks.”
Token count: [21]
Explanation: The tokenizer split this sentence into 21 tokens, showing that an AI model processes chunks of text rather than simply counting words.
2.	Context overflow
After a long conversation, I asked the model to recall “PURPLE-GIRAFFE-7291” from the beginning, and it could no longer retrieve it correctly.
Explanation: The conversation exceeded what the model could keep available in its active context, so information near the beginning was lost.
3.	Temperature / creativity comparison –
Normal response: [Mellow Cup, Afterglow Coffee, Quiet Hours]
More creative response: [Moonmilk Café, Dark Side Roasters, Luna After Midnight]
Explanation: The more creative run produced less predictable and more unusual answers, illustrating how increased randomness can change model output.
4.	Hallucination
Claim: The model claimed that The Second World War by Antony Beevor is a reliable catalogue source for the book about the second world war.
Verification: I checked] and found that the source did not give a punctual answer, as there are lot of books about the second world war and it was not specified which one I meant, the model should have asked back.
Explanation: The giveaway was unverifiable, because the model provided convincing-looking details for an unspecified vague question. 
