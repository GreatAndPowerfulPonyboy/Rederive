## Problem Statement

### Domain

My problem domain of choice is self-regulated learning, where users create their own practice materials or grab good materials from others and generate a schedule for repetition in hopes of solidifying their understanding.

Some users are trying to memorize the meaning behind jargon related to their field of interest because it's a road block on their path of understanding. While they are learning new material, they find words or symbols that they don't understand and Google their definitions. They determine whether it's important enough to remember, and place the worthy information into some structure that makes it easy to pick a chunk of words to memorize at a time.

Other users are attempting to solidify their understanding of the concept by constructing a set of prompts and responses. Their prompts are more related to the why and how of a topic instead of just the what. These prompts may include how one concept connects to another, why a certain tool is used in a specific situation, and common justifications for a decision within their field of study. In my opinion, what this user is attempting to build for themselves are a series of prompts and responses akin to a self-made oral evaluation for a given topic. The organization of prompts for this user can involve greater interconnectedness of topics as they attempt to have their prompts and responses represent their mental model of how different concepts connect.

### Bad Situations

#### Making flashcards is annoying/boring

A student is studying for a subject and finding a lot of words that they don't know. For every important word that they encounter, they have to make a card for the word and place it into their organizational system. The process of making a card is boring, and doing so for as many times as they need is tedious. This pain is felt with every card and with every review session, so it can lead the user to not make important cards, and to just trust that they'll remember when the time comes, which can lead to forgetting important information.

#### Made too many flashcards / skipped too many reviews

A user built up a large amount of flashcards over some period of time, but got busy and didn't have the time to engage in review for a week or two. As a result, they've built up a large backlog of flashcards and the task of reviewing seems daunting. This creates anxiety around reviewing that exacerbates the problem, leading to the user feeling more stressed than if they had not been consistently making cards.

#### Didn't improve grades

A user created a series of flashcards for a given subject, only to find that they still did poorly on the day of their exam. During the test, even if they remembered the surface-level definitions of key terms, they weren't able to synthesize that information well to handle whatever spins their teacher added to the subject. Since the creation and review of the cards imbued a higher level of confidence, their failure comes with an increased sense of shock and sadness than if they didn't make any cards at all.

### Corroboration

#### Boredom of flashcard review

- [Study in which a majority of the medical students researched used pre-made flash cards](https://pmc.ncbi.nlm.nih.gov/articles/PMC12662189/#sec3)
- [Larger study showcasing that over half of the studied students utilize pre-made flash cards in order to save time, but they recognize that the information isn't always trustworthy](https://sc-pan.github.io/pdf/ZIP_2022.pdf)
- [HackerNews article on the boredom of flash card review](https://news.ycombinator.com/item?id=24879467)
- [Post on r/anki asking for tips on how to make studying flashcards less boring](https://www.reddit.com/r/Anki/comments/1n5isk1/studying_flashcards_are_so_boring_not_a_rant_post/)
- [Post on r/languagelearning asking for advice on a more creative way to learn vocabulary](https://www.reddit.com/r/languagelearning/comments/1m18qa0/i_hate_flashcards/)

#### Skipped too many reviews

- [Study of Jordanian medical students that concluded that potential for burnout using Anki could result in a triage approach to review and/or a skipping of review sessions](https://pmc.ncbi.nlm.nih.gov/articles/PMC13126877/)
- [Different study on medical students using Anki that didn't demonstrate burnout potential](https://journals.sagepub.com/doi/10.1177/23821205231173289)
- [Reddit post containing advice on what to do when you've made too much of a backlog](https://www.reddit.com/r/Anki/comments/oh2tb3/too_many_anki_reviews_how_to_clear_an/)
- [Post on Anki forums describing how to make a filtered deck to tackle too many reviews](https://forums.ankiweb.net/t/too-many-cards-to-review-whats-the-best-way-to-tackle-this/23419/2)
- [Another post on the Anki forums with slightly different advice](https://forums.ankiweb.net/t/adressing-backlog/43842/2)
- [HackerNews post about an Anki backlog](https://news.ycombinator.com/item?id=22386479)

#### Didn't improve grades

- [Post on r/Anki reporting no improvement in grades despite consistent review](https://www.reddit.com/r/Anki/comments/1iw1yd8/anki_did_not_improve_my_grades_at_all/)
- [Post on r/medicalschoolanki asking why the poster isn't seeing results from Anki](https://www.reddit.com/r/medicalschoolanki/comments/oewzo0/why_im_not_seeing_results_from_using_anki_getting/)

### Workarounds and Comparables

#### Workarounds for avoiding card creation

Users often use a pre-made deck of prompts and responses in order to avoid the tedium of typing them up on their own. However, studies have shown that the process of creating the card itself confers learning benefits, so these users are missing out on their real goal in order to reduce some friction.

Other services such as Remnote allow for the easy AI-generation of flashcards, which also deprives of learning opportunities while introducing unique quality control concerns.

#### Workarounds for queue buildup

To handle queue buildup, users generate custom study schedules to filter out cards that they don't want to deal with. Not only does this require a certain level of fluency with the tool in particular, it also allows users to cheat by removing important, but difficult to remember, topics from their schedule. Users that aren't knowledgeable about how to create a custom schedule may instead delete prompts entirely, which leads them back into the first bad situation of having to make them again.

#### Workarounds for bad scoring / lack of transfer

A particularly demoralized learner may give up on the topic entirely if the effort they put into generating their own learning schedule didn't confer any benefits. A learner may also go back to paper-and-pencil tools, giving up on the ability for software to keep track of which topics were missed in a previous study session.

#### Comparables

Anki is the leader in spaced-repetition scheduling, but its default settings are punishing for missed reviews and its more powerful features are hard to learn. However, it provides lots of flexibility in the style of prompt and response, which can give motivated users powerful tools to stave boredom. Remnote and Obsidian provide a way to embed flashcards within one's notes, which simplifies the workflow and keeps learners engaged by always having the context of what they wanted to remember nearby.

### Solution Sketch

One way to solve the problem of creating cards being boring would be to attach some signal toward being a good prompt-maker. If users feel as though their creation of prompts solidifies them as part of some learning community, it won't feel like a chore. Furthermore, if one could connect this community-based prompt creation to the removal of a backlog users wouldn't face excessive buildup. Lastly, it'd be useful if this signal for being a good prompt-maker conveyed information on how well the person who made the prompt understands the topic. To some extent we have this in traditional test-taking. To make a good test, you need to have a good understanding of what material is worth learning, as well as the dimensions by which it can be evaluated.

My proposed way of mixing these concerns is a system where users join learning communities for their subjects of choice and there is an internal ranking system within that community of the best prompts for a given topic. During a review session, learners can compare their accuracy on the prompts they create for a given topic to those other users create, and the system varies the proportion of either automatically.
