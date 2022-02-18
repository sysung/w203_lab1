# Rubric 

## Introduction (4 levels) 

4. An introduction that is scored in the top level has very successfully made the case for the reader. It will have placed the specific question in context, connected the problem with the statistics and data that will be used, and have generally created a compelling case for continuing to read the report. 
3. An introduction that scores in the third level has done a significant amount of successful work. The reader can place the topic area and the research question; understand and appreciate why this is a question that demands a data based answer. Keeping this introduction from a full, four-point score might be: small issues with writing, some lack of continuity in the argument, or some other such small issue that keeps this from being a wholly convincing introduction. 
2. An introduction that scores in the second level has made some attempt to describe the problem and its importance, but it is missing significant parts of this argument. The language might be poorly chosen, the argument loosely formed, or the context left unexplained; there is considerable room for improvement. 
1. An introduction that is scoring at the first level either doesn’t exist, or has given a very cursory treatment for the setting of the question and why an answer based on statistics is necessary. 

## Conceptualization and Operationalization (4 levels) 

4. A report that is scored in the top level on conceptualization and operationalization will have done a wholly adequate job connecting the context and research question from the introduction to a set of clearly, and precisely defined concepts. From these concepts, the report will have identified data that clearly does a good job of measuring these concepts; the argument will be clear, concise, and complete. 
3. A report that is scored in the third level on conceptualization and operationalization will have done good work to define a concept and a measure that corresponds to that concept. Keeping this report from full marks might be some imprecision in the definition of the concept; or some mis-match between the concept and the eventual data that is used. 
2. A report that scored in the second level on conceptualization and operationalization will have attempted to connect the introduction into defined concepts; and will have also attempted to find measures in the data that map onto those concepts, but will have run into significant challenges. Either the concepts are not developed enough for any measure to be meaningful; or the choice of measure does not match with the concept. 
1. A report that is scored in the first level conceptualization and operationalization will have failed to connect the concepts that have been identified in the introduction to the data in any meaningful way. As a consequence, it is not possible for the reader to know that any analysis that comes from this report has any bearing on the question at hand. 

## Data Wrangling (3 levels) 

3. A report that is scored in the top level on data wrangling will have succeeded -- relative to expectations at this point in the course -- to produce a modern, legible data pipeline from data to analysis. The wrangling could be done in the same notebook as the analysis; or, perhaps the wrangling has be refactored into its own, more modular, `.R` file. The analysis should have a single source of truth data, and it should be clear what and how, any additional features are derived from this data. At this point in the course, a three point data wrangling can still have issues that keep it from being professional-grade, but these are the types of issues that might be expected for early-programmers: variable names might be communicative, but clumsy; pipelines might work, but be inefficient, etc.
2. A report that scores in the second level data wrangling will have tried, but not fully achieved the aims for a modern, legible data pipeline from data to analysis. None of the problems cast doubt on the results, but might mean that it would be difficult to contribute to this project in the future, difficult to read this analysis for the present reader, or some other such flaw. This level of data wrangling might have several version of the data that do not maintain referrential integrity (in the case of this data, an example of a problem is writing code based on column position rather than column names), or it might have several versions of derived data from the source data (i.e. `anes_data_republicans`, `anes_data_democrats`) that could generate issues with a future pipeline.
1. A report that scores in the first level on data wrangling has significant issues in how the data has been prepared for analysis. The data may choose to use inappropriate, or non-descriptive variables; may have made several mis-steps in the data preparation; or otherwise made choices in the preparation of the data that cast doubt on any results that might come from the analysis. 

## Data Understanding (3 levels) 

In order for a reader to understand or ascribe meaning to your results, they need to understand enough about the data that they can place what you are presenting to them in context.  This can be done with by referencing tables, figures, and summary statistics in the narrative.

3. A report that is scored in the top level on "Data Understanding" will describe features of the data in the narrative to give the reader sufficient understanding of the distribution.  Anomalies will be identified, including censored scales, artifacts of binning, and prominent clusters.  Every single plot or R output included in the report will be discussed in the narrative.
2. A report that is scored in the second level on "Data Understanding" will leave the reader with a good understanding of the data distribution.  Keeping the report from a perfect score might be a failure to comment on some feature of the data that would help the reader to contextualize the results.
1. A report that is scored in the first level will leave the reader with an insufficient understanding of the distribution to fully contextualize the results.  A report that includes an output dump (a plot or R output that is not discussed in the text) will also score in this level.


## Visual Design (5 levels)

5. A report that is scored in the top level will include plots that effectively transmit information, engage the reader's interest, maximize usability, and follow best practices of data visualization.  Titles and labels will be informative and written in plain english, avoiding variable names or other artifacts of R code.  Plots will have a good ratio of information to space or information to ink; a large or complicated plot will not be used when simple plot or table would show the same information more directly.  Axis limits will be chosen to minimize visual distortion and avoid misleading the viewer.  Plots will be free of visual artifacts created by binning.  Colors and line types will be chosen to reinforce the meanings of variable levels and with thought given to accessibility for the visually-impaired.  
4. A report that is scored in the fourth level will include plots that effectively transmit information, do not present major obstacles to usability, and follow best practices for data visualization.  Keeping the report from top score might be some distracting visual artifact, axis labels that do not line up properly with histogram bars, poorly chosen bin widths, a legend that conceals important information, or some other aspect in which the plot might be improved.
3. A report that is scored in the third level will include plots that contain important information and can be effectively used by most readers.  Keeping the report from a top score might be an instance in which a complicated or large plot is used when a compact plot or table would display the same information more effectively, redundant plots that substantially overlap in the information they show, or a moderate problem with axes, binning, labels, or colors.
2. A report that scores in the second level will have chosen a plot that communicates a point to the reader, but that could be more convincing in its effect.  The plot may not have multiple issues that interfere with usability; it may be poorly titled and labeled; or the choice of presentation may not have fully communicated the pattern that the team wants to make. 
1. A report that is scored in the first level will have serious issues with its visual design.

## Stating a Hypothesis (4 levels) 

4. A report that is scored in the top level on framing a hypothesis will have precisely stated the correct null hypothesis for the conducted test.
3. A report that is scored in the third level will have expressed a null consistent with the conducted test. Keeping this hypothesis from scoring full points might be a small lack of the precision; misapplied technical language, or some other flaw that doesn't detract from the broader conceptualization of the test.
2. A report that is scored in the second level will have stated a hypothesis, but it might be loosely related to the question at hand; unclear, or insufficiently precise to serve as a testing basis, or some other serious issue. 
1. A report that is scored in the first level will have significant problems with how the null hypothesis is stated. Either it will be incorrectly stated as an alternative hypothesis; or, it will be unrelated to the question at hand; or some other major flaw. 

## Arguing for, and Assessing a Test (6 levels) 

6. A report that is scored in the top level will have made a clear argument for the statistical test that is appropriate given the data, and the process that generates that data. This argument will be clear, precise, and correct. If there are limitations of the test, these will be identified, and reasoned about, but the report will be correct that this is the most appropriate test that can be conducted with this data. 
5. A report that is scored in the fifth level  will have made a clear argument for the statistical test that is appropriate given the data, and the process that generates that data. This argument will be clear, precise, and correct. If there are limitations of the test, these will be identified, and reasoned about, but the report will be correct that this is the most appropriate test that can be conducted with this data. Keeping this argument from full points might be very small imprecision in language or statistics; but the test is correct despite these small issues. 
4. A report that scores is scored in the fourth level will have made an argument for a test, and this argument might be somewhat reasonable but there is significant room for improvement or errors in presentation. For example, metric data might be interpreted as ordinal; or, ordinal data as metric (which is a more serious problem). Or a test might be close to correct, but could instead have utilized a universally better powered test. 
3. A report that scores either in the second or third level will have serious errors in its reasoning about a test. It might use data that is an inappropriate level, or a test that doesn’t inform the question at hand. There is considerable room for improvement in an answer of this form. 
1. A report that scores in the first level will have made very serious errors in its reasoning about a test. This might mean using a test that is unrelated to the question; or a test that is inappropriate to the data or some other very serious error that precludes any result from this test being able to inform the research question. 

## Test Results and Interpretation (6 levels) 

6. A report that scores in the top level will have interpreted the results of the test appropriately, drawn a conclusion about statistical significance; placed these results in context with some statement about practical significance that is compelling to the reader; and will have done so in a way that is clear, concise, and correct. 
5. A report that scores in the fifth level  will have interpreted the results of the test appropriately, drawn a conclusion about statistical significance; placed these results in context with some statement about practical significance that is compelling to the reader. Keeping this from full points might be some lack of clarity or concision; or some very slight error in the interpretation of the test. 
4. A report that scores in the fourth level will have done much of the testing correctly, but might be missing either a statement of practical significance or interpretation of the results of the test. While the statistics might not be incorrect, they are not making a wholly compelling argument. 
3. A report that scores in the third level will have some considerable errors in the testing. Either the results will be inappropriately interpreted -- statistically significant results might be interpreted as non-significant for example -- or will have failed to successfully connect the results of the test with an interpretation of what these results mean. 
2. A report that scores in the second level will have very serious issues with how the test results are interpreted. They may be wrong; non-existent; mischaracterized; or some other such very serious issue. If there is any interpretation, it might be incorrect or unhelpful. 
1. A report that scores in the first level will have very serious issues with how the test results are interpreted. They may be wrong; non-existent; mischaracterized; or some other such very serious issue. If there is any interpretation, it might be incorrect or unhelpful. 

## Overall Effect (3 levels) 

3. A report that scores in the top level will have met expectations for professionalism in data-based writing, reasoning and argument for this point in the course. It can be presented, as is, to another student in the course, and that student could read, interpret and take away the aims, intents, and conclusions of the report. 
2. A report that scores in the second level will be largely professional; largely clearly written and structured; but will have some problem that inhibits the reader from being able to clearly reason from the report. 
1. A report that scores in the first level will have significant issues in its presentation. These could be spelling, language, argument, formatting, or other issues that cause problems for the reader in their ability to read, evaluate, and take action on what is reported. 

