# 97_things_every_programmer

1:  Act with prudence: When under time pressure you can find yourself having to choose between "doing it right" and "doing it quick". The task may be completed quickly while making an honest promise to come back to it later... This is known as deliberate technical debt. The longer you leave it, the worse it gets. Pay off technical debt as soon as possible.

2: Apply functional programming principles: Master the functional programming pagadigm so you are able to judiciously apply the lessons learned to other domains.

3: Ask, "What Would the User Do?" (You are not the user). You'll find that there's a gap between what users say they want and what they actually do.  It's why the best way to capture requirements is to watch users.

4: Automate your coding standard.

5: Beauty is in simplicity.

6: Before you refactor: take stock of the current codebase, avoid the temptation to rewrite everything, make incremental iterations and test.

7: Beware the share: take care when pulling out shared code into a separate libary. You may be preventing libraries using this code to evolve independently.

8: The Boy Scout Rule: Always leave the campground cleaner than when you found it.

9: Check your code first before looking to blame others.

10: Choose your tools with care.

11: Code in the language of the domain: naming matters / conveys information. Don't make others guess what you mean.

12: Code is design.

13: Code layout matters: easy to scan, expressive layout, compact format. Auto formatting and conformance with style guides.

14: Code reviews: increase code quality and reduce defects. Instead of simply correcting mistakes in code, the purpose of code reviews should be to share knowledge and establish common coding guidelines. Code reviews will flow more easily if the team has coding conventions that are checked by tools.

15: Coding with reason.

16: A comment on comments: comments are necessary for programming, but you can go too far.

17: Comment only what the code cannot say: a comment has zero (or negative) value if it is wrong. As the codebase evolves comments may not get updated to the point where they could be misleading. Try to express as much as possible through code.

18: Continuous learning. 

19: Convenience is not an -ility.

20: Deploy early and often.

21: Distinguish business exceptions from technical.

22: Do lots of deliberate practice: Research over the last two decades has shown that the main factor in acquiring expertise is time spent doing deliberate practice. Innate ability is not the main factor.

23: Domain specific languages: always take the target audience into account.

24: Don't be afraid to break things.

25: Don't be cute with your test data: when writing any text in your code- whether comments, logging, dialogs, or test data - always ask yourself how it will look if it becomes public. It will save some red faces all around.

26: Don't ignore that error.

27: Don't just learn the language, understand the culture.

28: Don't nail your program into the upright position: Beware the try, except, pass...

29: Don't rely on 'magic happens here': Another department was running smoothly - projects delivered on time, no late-night debugging sessions, no emergency fixes. So smoothly, in fact, that senior management decided that things 'ran themselves', and it could do without the project manager. Within six months, the projects in the department looked just like the rest of the organization - late, buggy, and continually being patched.

30: Don't repeat yourself (DRY).

31: Don't touch that code: if it's broke, production is not the place to fix it.

32: Encapsulate behavior, not just state.

33: Floating-point numbers aren't real: since floating-point numbers are approximations of real numbers, there is inevitably a little error present. This error, called roundoff, can lead to surprising results.

34: Fulfill your ambitions with open source.

35: The golden rule of API design: it's not enough to write tests for an API you develop; you have to write unit tests for code that uses your API.

36: The guru myth.

37: Hard work does not pay off: if you just set off in one direction, running as fast as you can, you might impress some, but you are not likely to succeed. You need to keep a sustainable pace, and you need to adjust course when you learn more about where you are and where you are heading.

38: How to use a bug tracker.

39: Improve code by removing it: YAGANI - You Aren't Gonna Need It.

40: Install me: convenient install and docs.

41: Interprocess communication affects application response time.

42: Keep the build clean.

43: Know how to use command line tools.

44: Know well more than two programming languages.

45: Know your IDE.

46: Know your limits.

47: Know your next commit: have a manageable incremental step in mind.

48: Large, interconnected data belongs to a database.

49: Learn foreign languages.

50: Learn to estimate.

51: Learn to say 'Hello, World' ...

52: Let your project speak for itself: it's effective to embody the project in your office by using an extreme feedback device (XFD).

53: The linker is not a magical program.

54: The longevity of interim solutions: they're useful but can acquire inertia. The interim solution can remain in place ... forever. Should you change it? Is it a problem?

55: Make interfaces easy to use correctly and hard to use incorrectly.

56: Make the invisible more visible: It's best to develop software with plenty of regular visible evidence.

57: Message passing leads to better scalability in parallel systems.

58: A message to the future: Think of every line of code you write as a message for someone in the future - someone who might be your younger brother. Pretend you're explaining to this smart person how to solve this tough problem.

59: Missing opportunities for polymorphism: Used carefully, polymorphism creates tiny localized execution contexts that let us work without the need for verbose if-then-else blocks.

60: Testers are your friend.

61: One binary: build a single binary that you can identify and promote through all stages in the release pipeline.

62: Only the code tells the truth: ask youself how clearly your code is telling you or any other programmer what it is doing. Comments are not running code and can be just as wrong as other forms of documentation. Strive for good names, write automated tests, refactor mercilessly.

63: Own (and refactor) the build: the code is useless without being built. Build scripts are code. 

64: Pair program and feel the flow.

65: Prefer domain specific types to primative types.

66: Prevent errors: offer selection widgets for data rather than expecting raw user input. Provide cues on the desired format, defaults where possible.

67: The professional programmer: you are responsible for your career, learning, code quality...

68: Put everything under version control.

69: Put the mouse down and step away from the keyboard: the trick is that while the logical side of your brain is coding the creative side is shut out. It can't present anything to you until the logical side takes a break.

70: Read code.

71: Read the humanities: prople write software with people for people. It's a people business.

72: Reinvent the wheen often: Reinventing the wheel and getting it wrong is more valuable than nailing it first time. There are lessons learned from trial and error.

73: Resist the temptation of the singleton pattern.

74: The road to performance is littered with dirty code bombs.

75: Simplicity comes from reduction. The code should be simple... extra anything should be purged.

76: The single responsibility principle: A subsystem, module, class or function should not have more than one reason to change.

77: Start from yes.

78: Step back and automate, automate, automate.

79: Take advantage of code analysis tools.

80: Test for required behavior, not incidental behavior: When tests are wired to implemention incidentals, changes to the implementation that are actually compatible with the required behavior may cause tests to fail, leading to false positives. Overspecified tests are often a problem with whitebox approaches to unit testing. Whitebox tests use the structure of the code to determine the test cases needed.

81: Test precisely and concretely.

82: Test while you sleep (and over weekends): Are you constantly finding it difficult to get enough computing power during the work day? If so, what are your test servers doing outside of normal work hours?

83: Testing is the engineering rigor of software development.

84: Thinking in states. Study the state pattern. When you are comfortable, read up on Design by Contract.

85: Two heads are often better than one. Being the expert technologist is no longer sufficient. You must become effective at working with others. I'm a big fan of pair programming.

86: Two wrongs can make a right (and are diffucult to fix): The interplay between two code defects that appear as one visible fault not only makes it hard to fix the problem, but also leads developers down blind alleys, only to find they tried the right answers early on.

87: Ubuntu coding for your friends.

88: The Unix tools are your friends.

89: Use the right algorithm and data structure.

90: Verbose logging will disturb your sleep. Too much logging can be as useless as none at all.

91: WET dilutes performance bottlenecks. The antithesis of DRY is WET (Write Every Time). With WET, we have 10 different implementations that we need to find and fix and the performance bottleneck is harder to see.

92: When programmers and testers collaborate. The magic of successful teamwork begins.

93: Write code as if you had to support it for the rest of your life.

94: Write small functions using examples.

95: Write tests for people. Good tests act as documentation for the code they are testing.

96: You gotta care about the code. Good programming lies in taking a professional approach and wanting to write the best software that you can.

97: Your customers to not mean what they say. The problem is that customers don't always tell you the whole truth. They use customer speak, not developer speak. So how do you deliver a software product under these circumstances? Interact with them more. Discuss requirements in detail from the outset. Get feedback early and often.
