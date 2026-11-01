# How to Answer "Explain a Technical Concept to a Non-Technical Person"

Engineers, analysts, product managers and data scientists all get some version of this question: "Explain an API to my grandmother," "How would you describe a database to a new salesperson?" or simply "Pick something technical and explain it to me like I'm not technical."

The interviewer is not testing whether you know the concept. They assume you do. They are checking whether you can work with people outside your team: stakeholders, customers, executives. A correct but jargon-heavy answer fails this question.

## What a good answer does

1. **Starts with why it matters to the listener.** Lead with the problem the concept solves, not how it works.
2. **Uses one everyday comparison.** A single clear analogy beats three half-finished ones.
3. **Drops the jargon, or defines it once.** If you must use a term, explain it in a short sentence.
4. **Checks for understanding.** Ending with "Does that make sense, or should I go a level deeper?" shows you read your audience.
5. **Stays short.** About one minute. You can always add detail when they ask.

## A simple structure

- **One sentence on the purpose:** "An API lets two pieces of software talk to each other without knowing how the other one is built."
- **One comparison:** "It works like a restaurant menu. You don't go into the kitchen; you pick from the menu, the waiter takes the order, and the food comes back."
- **One concrete example from their world:** "When our sales dashboard shows today's orders, it is asking the order system's API for that list."
- **A check-in:** "Want me to go into how we keep that secure?"

## Example answer: explaining caching

> "Caching means keeping a copy of something you use often close at hand, so you don't have to fetch it from far away every time. It's like keeping a water bottle on your desk instead of walking to the kitchen for every sip. Our app does the same with product prices: instead of asking the main database every time a page loads, it keeps recent prices in fast memory, so pages load in a fraction of a second. The trade-off is that the copy can be slightly out of date, so we refresh it every few minutes. Would it help if I explained how we decide how often to refresh?"

Why it works: purpose first, one analogy, a real example, the trade-off in plain words, and a check-in.

## Example answer: explaining machine learning

> "Machine learning is a way of teaching a computer by showing it lots of examples instead of writing every rule by hand. If you wanted a program to spot spam, you could try to list every spam phrase, but spammers keep changing them. Instead you show the program thousands of emails already marked spam or not spam, and it learns the patterns itself. It's similar to how a new hire learns what a good customer ticket looks like by reading a few hundred old ones. It isn't perfect, so we still review the cases it's unsure about."

## Mistakes to avoid

- **Explaining how before why.** Nobody cares about the request format until they know what an API is for.
- **Stacking analogies.** A menu, then a mail carrier, then a phone line gets confusing fast.
- **Talking down.** "It's really simple" can sound condescending. Just make it simple.
- **Going too long.** If you pass two minutes without a check-in, you have lost most listeners.

## How to practice

Pick three concepts from your own work and write a five-sentence explanation for each using the structure above. Then explain one to a friend outside your field and ask what they would repeat back to someone else. Recording yourself or practicing with an AI tool also helps you notice where you slip back into jargon.

*Disclosure: I work on Linkjob AI, which offers [real-time interview help](https://www.linkjob.ai/) and practice tools. The approach above works with or without any tool.*
