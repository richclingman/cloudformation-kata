# cloudformation-kata
Repeatable learning sessions for mastering AWS CloudFormation.

## IMPORTANT: THERE WILL BE COSTS
If you deploy the templates as you work through these katas,
you will incur costs from AWS for the resources you create.

Be certain you DELETE the stack of resources immediately
after you're finished with the kata.

You may be eligible for a 
[free tier account](https://aws.amazon.com/free/)
from AWS.
This will not guarantee everything you create here is free.
You are responsible to control your costs.
You should also 
[set a billing alarm](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/monitor_estimated_charges_with_cloudwatch.html)
so you are alerted if you leave resources that are
costing you money.

## How to Use
Create a *fork* from this github repo.
That way you can commit code to your own repository
as you work through the kata.

## Kata Concept
The idea of a kata is to repeat an action so often that it becomes automatic. 
This means that we repeat an exercise so often that we're able to complete it 
in minimal time with minimal assistance (from Google, etc.).

## CloudFormation
CloudFormation is a Infrastructure As Code (IAC) tool within Amazon Web Services (AWS).
Using CF we can build infrastucture, create users, deploy servers, and more.

## Assumption
I'm assuming you have a personal or business account
that you can use to work this kata.


You'll need to have CLI credentials.

[How to create CLI credentials](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-getting-started.html)

## Working the Kata
Under the kata directory are the kata exercises.
They're numbered to add complexity as skills are learned.

For each kata there is a 

goal.md -- The objective and concepts to learn.

solution.json -- One solution for meeting the objectives.

attempt.json -- You create this file

## First Attempt
For your first attempt, review the included solution.json CF template file.

Things to note: A CF template always requires a Resources section.
It is the only required section. 
All other sections are optional.

## Kata Repetition
The kata concept is to repeat the exercise until you have coding muscle memory.

As necessary, refer to solution.json for guidance. 
As you learn the concepts, refer to AWS resources rather than the solution.json.

[AWS CloudFormation Documentation](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/Welcome.html)

* Create a new ec2-instance.json
* Add code to meet the objectives
* Deploy the template

## Manual Deploy 


## Continuous Delivery
Kata ### shows how to set up a CD pipeline
for deploying CloudFormation templates.
Using the CD pipeline, you can deploy a stack simply
by committing and pushing your template.

See Kata ### for more information.

#### Be certain to delete your stacks that are created by CD!

# Rich Clingman
[https://github.com/richclingman]

[https://linkedin.com/in/richclingman]

[https://twitter.com/richclingman]
