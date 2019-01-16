# <img src="http://www.rice.edu/_images/rice-logo.jpg" width=180> Comp427, Spring 2018, Homework 1
## Rational Paranoia
The homework specifications, as well as the corresponding course slide decks,
can be found on the [Comp427 Piazza](https://piazza.com/class/jqifhp864b37ju).
This assignment is due **Thursday, January 17 at 6 p.m.**

You will do this homework by editing the _README.md_ file. It's in
[MarkDown format](https://guides.github.com/features/mastering-markdown/)
and will be rendered to beautiful HTML when you visit your GitHub repo.

## Student Information
Please also edit _README.md_ and replace your instructor's name and NetID with your own:

_Student name_: Edward Feng

_Student NetID_: jf44

Your NetID is typically your initials and a numeric digit. That's
what we need here.

_If you contacted us in advance and we approved a late submission,
please cut-and-paste the text from that email here._

## Problem 1
- Scenario: {Stadium}
- Assumptions:
  - Assume a lot of people are coming to watch the game in this stadium, since
    the team is frequently ranked among the best in the country.
    Also assume that we have a really professional security team with all of the
    necessary equipments available.
    Also assume that we know what team are the fans rooting for when we sell them
    the tickets.

- Assets:
  - The safety of the people watching the game in the stadium. This is definitely
    the most important one since there will be a significant amount of audience
    in the stadium when there's a game.
  - The safety of the players playing in the game. The players are the people who
    generate the profit so we definitely need to make them safe.
  - The facility inside of the stadium. The stadium is a huge and complicated 
    system that has a lot of important facilities which need to be safe.
  - That the game runs smoothly without interruption. The people paid to watch a 
    smooth game and the players trained for playing a smooth game. We need to make
    sure that both groups get what they deserve.

- Threats:
  - Malicious people sneaking into the stadium threating people watching the game.
    There might be malicious people trying to get into the stadium and use dangerous
    items or even weapons to threat other people.
  - Fans for different teams fighting against each other. Fans can be crazy sometimes.
  - Malicious people interrupting the game (cut electricity etc.) There are always
    some people who are trying to interrupt the game. They might cut the water or
    electricity etc.

- Countermeasures:
  - For the first and the third threats, we need to set security check at every
    entrance of the stadium to make sure that nobody brings dangerous stuff into
    the stadium. The cost might be a little high considering we need to get the
    professional equipments for things like scanning and detecting. But the benefit
    is enormous as it can help us avoid so many problems in the stadium.
  - To avoid fans for different teams fighting each other. We can try to put them into
    different sections when we assign them seats, as we assumed that we know who they
    are rooting for. The cost is not that high here and the benefit is decent. But the
    assumption that we made is critical, otherwise we wouldn't know how to separate these
    fans.
  - To avoid people interrupting the game, we need to make sure that we have our security
    people patrolling around the stadium, especially around the critical areas. The cost
    is not that high and it should be enough to address issues that are not so serious.
    Also for threats like power cut, we need to have a backup system in case there's 
    emergency. The cost of this might be really high, but the benefit is also enormous,
    since it guarantees that the game runs smoothly.



## Problem 2
- Scenario: {Grading}
- Assumptions:
  - The homework is submitted and graded using some online system.
  - The homework solution is not shared to anybody, only the grader knows, and it is
    no where online.
  - There exists some software or it is possible to develop some software that checks
    plagiarism.

- Assets:
  - The integrity of the grades. The grades must remain what they are and cannot be
    modified by anybody. Make sure that only I, along with other graders can change
    the grade.
  - The authenticity and integrity of the homework. Once homework is due, they can't
    change it anymore and the homework must be their authentic work. There shouldn't
    be any plagiarism.

- Threats:
  - System hack. Some students might try to sneak into the system and change their grades.
    In this case the graders are no longer the only people who can edit the grades.
  - Cheating. Some students might keep working on the homework after it is due, this
    would happen especially when the homework is submitted online. Some students might
    copy other students homework entirely, which is plagiarizing.

- Countermeasures:
  - Build a robust online grading system that uses sophisticated authentication system,
   maybe two factor authentication, when we're trying to change the grade, and only the
   graders have access to these special authentications (the two factor authentication app
   can only be installed on the graders' cell phones). The cost might be a little high but
   it is super necessary because having other people messing around with the system definitely
   needs to be avoided.
  - We can keep a time stamp whenver something got edited or submitted. Then when we're grading
    them, we need to double check the time stamp on each submitted homework. This is not hard to
    achieve and should bring really essential benefits to us. For plagiarism, one way is that we
    can manually check every single pair of homework, which requires significant amount of human
    work and is probably not worth it. We can also develop or purchase some software to do this,
    it might be costly but can save up a lot of human hours. The benefit of doing this is also
    essential, as avoiding plagiarism is one of the main focuses in today's education and academia.



## Problem 3
- Scenario: I'm supervising the election system of the U.S. president election.
- Assumptions:
  - The election is highly decentralized and there are hundreds, thousands of voting machines.
  - The election mostly happens electronically through the internet.
- Assets:
  - The integrity of the votes in the online system. 
    Nobody can change the votes and the system must make sure
    that the result is a correct representation of what people actually voted. There cannot
    be a single error, otherwise the result cannot be trusted.
  - The robustness of every single voting machine. Since voting can be a highly decentralized
    activity, and it is broken down into very small local regions, we must make sure that the
    individual voting machines be secure and robust to make sure that the overall election result
    is valid and representative.
- Threats:
  - System hacks. There might be people who hack into the election system and change the votes,
    or they can change the way that election system operates so that it is no longer fair and valid.
    Even if one machine got hacked, the overal result can be distorted.
  - Repetitive votes. Some people might vote multiple times thus distorting the election result, which
    needs to be avoided. One man one vote should be the strict rule that we all follow.
  - Social media manipulation. People might create rumor on social media to create bias in people's mind.
    Such as some group of people might make up rumor to undermine the reputation and credit of certain 
    political party.
- Countermeasures:
  - For the first and the second threats, the most important thing is to build robust and secure software
    systems and database systems such that the election system can be trusted to operate in a good manner.
    We also need to have plenty of security engineers, hackers, working simultaneously while the election
    goes to make sure that even if there's any issue showing up, we can still make it up as soon as possible.
    The cost might be high but this is absolutely worth it as it is something that will benefit the whole nation.
  - For the social media manipulation one, social media companies can hire special group of people to monitor the
    rumors being spreaded on the internet and delete those malicious contents. We can also develop machine learning
    algorithms to automatically classify the rumors and delete them. The first approach takes a significant amount 
    of human hours to achieve, but it will give us better result compared with the machine learning approach.
    Machine learning algorithms save a lot of human energy but it cannot be as robust as human checking sometimes.
    So the cost here is a tradeoff, and either way the benefit can be huge.

