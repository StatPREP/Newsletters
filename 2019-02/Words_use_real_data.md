Words from Danny

**Use real data.** That's a simple but profound recommendation from the American Statistical Association's guidelines for statistics instruction. In the [November 2018 issue of this newsletter](http://statprep.org/wp-content/uploads/2018/11/Back-to-School-Newsletter-11.01.pdf), I presented the operational definition of "real data" developed at StatPREP's Oct. 2018 meeting at the American Mathematical Association:

> Data is real when it has at least 1000 rows, at least 5 variables, and was not initially collected with a primary purpose of teaching statistics.

As appropriate for an operational definition, it is readily applied to any data set and provides a yes-or-no answer. There's no call to be fanatical about the numbers 1000 and 5; anything close will do. But the common textbook practice of using on the order of 10 rows and only one or two variables is not close.

Now it's time to talk about the meaning of the word "*use*" in the phrase "use real data." Much of the data that appears in textbooks is intended to provide numbers for statistical calculations. Any other numbers could be used instead. But there are far richer ways to make data central to a lesson or exercise, ways that involve the actual handling of data, the search for patterns or anomolies, data display, and the interpretation of data in its actual context. 

- The data should be "raw." That is, students should work directly with the data themselves rather than with a statistical summary. Statistics like means and proportions are not data but *summaries of data*. 
- The data should be in a professional form. It's important for students to learn about the conventional ways in which data are organized, the most important of which is as a spread-sheet like table, with a columns for each variable and a row for each "unit of observation." They should see examples of good practice, for instance putting meta-data such as measurement units and descriptions in a separate codebook file. 
- The data should be rich enough to reward exploration and encourage hypothesis *formation*.

As an example, consider polling data. I'm not talking about the summaries of polling data that we see in the news and textbooks, such as p-hat = 48% and n = 893. Instead, think about the raw data that lies beneath such summaries. As an example, the file <https://www.dropbox.com/s/xfupf3n5mscpg9z/Montana_poll.csv?dl=0> contains the 578 survey responses collected in a poll prior to a 2017 special election for a vacated congressional seat in Montana. The political choice of the person surveyed is just one of the variables. Others include the sex and age-group of the respondant, his or her location in the state, the number of milliseconds it took to give a response to the question, the time-of-day of the response. There's also a demographic "weight" for the respondant, which can support a conversation about sampling bias. (How was the weight calculated? How might the weight be used?) You can do all the usual calculations of confidence intervals on proportion, but there are also questions to be answered such as how age groups differ or even whether Republicans or Democrats respond to the survey at different times of day. 

A data skeptic might ask, "In the end, doesn't it all boil down to $\sqrt{\hat{p} (1 - \hat{p}) / n}$?" Not insofar as you are answering questions about the real world. I found the Montana data in a news commentary about fake polls (<https://fivethirtyeight.com/features/fake-polls-are-a-real-problem/>) where the issue was how to recognize fraud by examining closely the raw data for inconsistencies or unrealistic clumping. In today's world, $\sqrt{\hat{p} (1 - \hat{p}) / n}$ is only a small part of the story.




The ASA GAISE report is available at `http://www.amstat.org/asa/files/pdfs/GAISE/GaiseCollege_Full.pdf`.