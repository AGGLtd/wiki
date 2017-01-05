# Branches

- branches allow a software project to divide work among its teams for concurrent development by isolating change \cite{bird2012branches}
- integrating changes from multiple branches can be difficult and error-prone, especially if changes on different branches conflict, either syntactically or semantically\cite{bird2012branches}
- branching patterns \cite{appleton1998streamed}

# Social Coding

- examples: GitHub, BitBucket
- Project networks are more interconnected than human networks \cite{thung2013github}
- Social coding enables substantially more collaborations among developer \cite{thung2013github}
- provides transparency in the form of visibility of others’ actions on public or shared artifacts~\cite{dabbish2012social}
- notifying members of actions on shared artifacts helps them maintain mental models of others activities~\cite{gross2005user}
- notifying members of actions on shared artifacts avoid potential coordination conflicts~\cite{sarma2003plantir}
- isolated development is bad because not knowing which artifacts are changing in parallel regularly leads to problems when changes are promoted from workspaces into a central configuration management repository.~\cite{sarma2003plantir}
- Social computing technologies shift the focus of interaction to individual contributors and their activities with electronic artifacts~\cite{dabbish2012social}

## Social Networking at Work
- Usage of Facebook and LinkedIn at work increases ~\cite{Skeels2009FacebookLinkedinAtWork}
- LinkedIn, ideally positioned for young professionals, is widely used to build and maintain external professional networks~\cite{Skeels2009FacebookLinkedinAtWork}
- motivations in doing this include connecting on a personal level with coworkers, advancing their career with the
company, and campaigning for their projects~\cite{DiMicco2008Newtworking}
- Within the walled garden of the enterprise, employees choose to reach out and meet new people rather than only
connecting to those they know.~\cite{DiMicco2008Newtworking}
- share details of their life outside of work which has not been found with any frequency in other enterprise social software tools~\cite{DiMicco2008Newtworking}
- If motivated by career advancement goals or a desire to champion a project idea, they use the social network site
strategically to connect and spread their message to a large audience~\cite{DiMicco2008Newtworking}

## GitHub PRs
- Most pull requests are less than 20 lines long and processed (merged or discarded) in less than 1 day~\cite{gousios2014PullBasedSD}
- the discussion spans on average to 3 comments, while code reviews affect the time to merge a pull request~\cite{gousios2014PullBasedSD}
- 14% of repositories are using pull requests on Github.~\cite{gousios2014PullBasedSD}
- In Ruby, Java and JavaScript, the average number of unsuccessful pull requests per month is exceptionally
higher than that of successful pull requests~\cite{rahman2014pullrequests}
- The rate of unsuccessful pull requests increases exponentially (for one project) with more than 4000 developers involved~\cite{rahman2014pullrequests}
- Many projects working with feature branches perform code reviews during pull requests before merging the changes into the main branch~\cite{driessen2010successful, calefato2015PLE, yu2015pullrequests, tsay2014contributionGithub, gousios2014PullBasedSD,tsay2014ContributionDiscussion}.
- Contributions that follow technical contribution norms are more likely to be accepted.~\cite{tsay2014contributionGithub}
- Contributions from submitters with a stronger social connection to the project are more likely to be accepted.~\cite{tsay2014contributionGithub}
- Contributions with a high amount of discussion are less likely to be accepted.~\cite{tsay2014contributionGithub}
- Acceptance of highly discussed contributions will be moderated by both social and technical factors.~\cite{tsay2014contributionGithub}
- Contributions from submitters with a high status in the general community are more likely to be accepted~\cite{tsay2014contributionGithub}
- Contributions from submitters that hold higher status in a specific project are more likely to be accepted~\cite{tsay2014contributionGithub}
- Contributions to established projects are less likely to be accepted~\cite{tsay2014contributionGithub}
- developers raised issues around contributions over both the appropriateness of the problem that the submitter attempted to solve and the correctness of the implemented solution~\cite{tsay2014ContributionDiscussion}


# Code Quality

- code ownership correlates with code quality \cite{greiler2015codeownership, bird2011codeownership, foucault2014codeownership, rahman2011ownership}

# Code Reviews
- Code Review is an important practice at Microsoft and in other companies and open source projects~\cite{balachandran2013PeerCodeReviews, bird2015CodeReviewPlatform, rigby2013PeerCodeReviews}
- code reviews allow a group of people to communicate over a shared view of an artefact undergoing a change \cite{czerwonka2015codereviews}

## Benefits
- Code review coverage and review participation share a significant link with software quality.\cite{mcintosh2014impact}
- Motivations are: finding defects, code improvements, alternative solutions, knowedge transfer, team awareness\cite{bacchelli2013expectations}
- Most of the comments are in the categories code improvements, understandability, social communication and defects. \cite{bacchelli2013expectations}
- Only about 15% of comments provided by reviewers indicate a possible defect, much less a blocking a code submission \cite{czerwonka2015codereviews}
- it is feedback related to the long-term code maintainability that comprises a much larger portion of comments provided by reviewers; at least 50% of all. \cite{czerwonka2015codereviews}

## Challenges

- forces the reviewer to switch context away from their current work \cite{czerwonka2015codereviews}
- the longer the review time, the harder is for the author to switch back to the change and incorporate the feedback of the reviewers without potentially introducing new defects\cite{czerwonka2015codereviews}

## Process
- effective code reviews should be performed by people with specific set of skills \cite{czerwonka2015codereviews}
- are standard part of modern software engineering \cite{czerwonka2015codereviews}
- 72.8 percent of the code lines were watched in the first 30 percent of the review time. \cite{uwano2006analyzing}
- the longer a reviewer scanned the code, the more efficiently the reviewer could find the defect in the code review \cite{uwano2006analyzing}
- Peer code review, a manual inspection of source code by developers other than the author, is recognized as a valuable tool for reducing software defects and improving the quality of software projects \cite{ackerman1989software}
- Developers believe that factors such as the experience of developers, the choice of a reviewer, size of a patch, its quality and rationale affect the time needed for review \cite{kononenko2016codereviewquality}
- bug severity, code quality and its rationale, presence and quality of tests, and developer personality impact review decisions.\cite{kononenko2016codereviewquality}
- in Mozilla: While most of developers write patches as well as review them, a dedicated group of developers is responsible for reviewing code changes. \cite{kononenko2016codereviewquality}
- Users are more likely to invest time in a solution if they know that the community is active and that they can get help when needed~\cite{bird2015CodeReviewPlatform}

### Convergent Practices
- Contemporary peer review follows a lightweight, flexible process~\cite{rigby2013PeerCodeReviews}.
- Reviews happen early (before a change is committed), quickly, and frequently.~\cite{rigby2013PeerCodeReviews}.
- Change sizes are small. Contemporary review is performed regularly and quickly just before the code is committed instead of when a larger work product is complete as in inspection~\cite{rigby2013PeerCodeReviews}.
- Two reviewers find an optimal number of defects. Contemporary review usually involves two reviewers. However, the number of reviewers is not fixed and can vary to accommodate other factors, such as the complexity of a change~\cite{rigby2013PeerCodeReviews}.
- Review has changed from a defect finding activity to a group problem solving activity. Contemporary reviewers prefers discussion and fixing code over reporting defects~\cite{rigby2013PeerCodeReviews}.

## Usefullness

- The usefulness of code review comments—as judged by the author of a code change—is positively correlated with reviewers’ experience \cite{czerwonka2015codereviews}
- Code review usefulness is negatively correlated with the size of a code review \cite{czerwonka2015codereviews}
 - The decrease however only starts to be noticeable for reviews with 20 or more changed files \cite{czerwonka2015codereviews}

# Related Work
- CodeFlow (Microsoft) ~\cite{bird2015CodeReviewPlatform}
- Palantir - continuously informing developers of the activities of others developers.~\cite{sarma2003plantir, sarma2012plantir}

## Pull requests & feature branches
- Many projects working with feature branches perform code reviews during pull requests before merging the changes into the main branch~\cite{driessen2010successful, calefato2015PLE}. 