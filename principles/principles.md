# Engineering principles

 These are the principles that we think are important for engineering at NICE Digital. They aren't "rules", they help us to prioritise our efforts on what is important.  Our principles and practises enable us to release new software quickly, safely and sustainably. 

 ## The master branch is always ready for production
Our source code trunk is always in a state of being ready for production.  It builds correctly, the tests pass and the deployment artifacts are created.  If our pipelines fail we fix this before other work.  This enables us to release changes safely and quickly when we need to.

 ## The code is not yours
 The code we write is owned by the team, not the author.  We write code with the needs of other developers in mind.  Code should be easily understood and maintained by developers in the future.  Code should clearly capture the intended behaviour of the system.  We write code to the best of our ability and the given contraints.  We appreciate that others can help to improve the code that we write.  Developers feel safe and empowered to point out problematic code.  When code is hard to understand we listen to the needs of others and improve it together.  

 ## Use standards from the start
 When starting something new, use our development standards from the beginning.  Understand the needs of the project and decide which standards are important.  Implement standards early and review them periodically.  Adopting standards retrospectively can be costly.  (TODO: Write standards for key areas such as front-end, accessibility, security etc)

 ## Use proven technologies - don't reinvent the wheel
Take advantage of the good work that others have done before you.  Use proven technologies to solve common problems. Don't waste time writing software for problems that already have proven technology solutions.  

 ## Work in the open
 Open source your code as early as possible.  Only make it private if there is a really good reason.  Be aware that open work is discoverable by others.  Use our [README template](example-readme.md) to ensure your overview documentation is appropriate and readable for different audiences.  Remember that non-developers need to be able to read our documentation too.
 (CAVEAT: Be careful not to commit credentials or personal information.  Use parameterisation to inject these)

 ## Share the knowledge
 If you have knowledge that is unique to you, you need to help share it.  Be open to sharing knowledge with your teammates.  Understand what others need to know and share it with them.  Assist your team on planning how to share knowledge.  Sharing knowledge benefits you, your team and the organisation.  

 ## Understand how well your software runs in production
 Distributed software systems are complex and your software will inevitably fail.  Make sure you have visibility of how well your software is running in production so that you can act accordingly.  Poorly performing software creates a bad user experience. 

 ## Agree on what quality means
 Understand the context of the problem you are solving.  Different applications will have different definitions of quality.  Agree with the team on the appropriate level of quality.  Track and measure quality.         

# We want your feedback
Are these any good? Anything you disagree with something or think something needs adding? open an issue or pull request :-)
