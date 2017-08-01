# Estimating Projects
Accurately estimating software development tasks is very hard. Humans are notoriously bad at predicting things they don't 
fully understand, so we decided to put together a list of suggestions to help improve the quality of the estimates we put every day for our clients. 

## What are we trying to build?
Before we are ready to estimate a project, we need to understand exactly what are we building. This doesn't mean that we need to know every single detail (actually, quite the opposite), but we do need a general idea with enough details to put together a compelling estimate:

* Don't give off-the-cuff estimates before you understand the full scope of the project. You are very likely to misestimate the effort and anchor your team to a number that has no substance behind it. 

* Spend as much time as possible trying to understand the requirements of the project. Write everything down and make sure you have a good handle on the full scope before starting the estimate.

* Make sure the scope has enough details to allow a project manager to drive the project comfortably. Requirements with too many details won't give the team enough room to maneuver, and requirements with not enough details will be tough to estimate. 

## Refining the list of requirements
After you have the list of requirements needed to build the product, spend some time following this list:

* Identify the essential features needed to make the product serve its purpose.

* Identify the least important features for meeting the client’s goals. These will be candidates to cut if you need to 
adjust the scope of the product.

* Identify features that might be overly expensive (in time or budget) and discuss a possible simple alternative.

* Identify potential internal and external dependencies to finish the product.

* Identify the risks and discuss a plan to mitigate them.

* Identify hidden features that are not explicitly mentioned in the client's request but are necessary to complete the product.

## Estimating the work
Now that you have a good idea of what exactly you are building, the next step is to estimate the individual features that are part of the scope of the project. Here are the things to keep in mind:

* Make sure the feature you are trying to estimate is clearly defined.

* Make sure you include in your estimate every type of work needed to complete the feature.

* Make sure all the features of your scope have a similar granularity. Avoid estimating small tasks together with larger and more complicated features. Instead, decompose your large estimates into small pieces to expose hidden work.

* Estimates should be approved by the person responsible for doing the work. This doesn't necessarily mean that the actual developer or designer has to sign off on the estimate, but avoid providing estimates outside your area of expertise.

* For each estimate, consider a productivity similar to what your team has been able to achieve in the past.

* For each feature, create an Optimistic Case, a Pessimistic Case, and a Most Likely Case to stimulate thinking about the full range of possible outcomes.

* Make sure to document all the assumptions in your estimate. 

* The larger the project gets, the more difficult will be to come up with accurate estimates based on time. Instead, use relative sizing ([Story Points](https://www.mountaingoatsoftware.com/blog/what-are-story-points)) whenever possible and derive the final estimate using your team's velocity.

## Making sure you don't forget something
Estimates should include all the necessary software development activities, not just design, coding, and testing. Keep in mind that nothing can be built for free, and your estimates shouldn't imply that it can. Make sure you run through these questions and adjust your estimates based on your answers: 

* How long will it take you to clarify all the requirements, document them, and prepare the backlog of the project?

* How long will it take to prioritize and size that backlog?

* If you need to put together an initial release plan, are you accounting for the time to do it?

* Are there any third-party integrations that will require further review and you aren't planning on it yet?

* Do you need to schedule any time to think about performance, scalability and the security of the project?

* Are you planning enough time to deploy the product?

* How much time do you need to transition the project to the client?

* Do you need to do any user training before handing over the project?

* Is there any data migration that you should include in your estimate?

* Are there any tools you will have to include as part of your costs?

* Is there any warranty period that should be planned and estimated?

## Putting everything together
Now that you have individual estimates covering the entire feature set you are trying to build, is time to put everything together and provide your overall estimate for the work. Your goal is to come up with three different outputs: *cost*, *schedule*, and list of *features*. To do this, keep the following in mind:

* Determine whether you need an _estimate_, a _target_, or a _commitment_. An _estimate_ is an unbiased prediction of how long a project will take or cost. A _target_ is a description of a desirable business objective. A _commitment_ is a promise to deliver defined functionality with a particular level of quality by a certain date. 

* Whenever you can, avoid providing a single-point estimate and try to provide a range instead. If you need to specify a single value, make sure the probability of hitting that number is aligned with your risk tolerance.

* Assuming you are using a range, avoid making it artificially narrow. Be sure the range you use doesn't misrepresent your confidence in your estimate.

* Do not intentionally underestimate. The penalty for underestimation is almost always more severe than the penalty for overestimation.

* Consider the effect of the [Cone of Uncertainty](https://en.wikipedia.org/wiki/Cone_of_Uncertainty) on the accuracy of your estimate. Your estimate cannot have more accuracy than is possible at your project's current position within the Cone.

## What to do if estimates are too high?
More often than not, your estimates might come too high, and you will have to find ways to cut them down. Here are some suggestions to keep in mind:

* Don't reduce developer estimates. They are probably too optimistic already.

* Don't simply cut the numbers down without discussing the consequences and the plan to mitigate them. You can negotiate (and reduce) commitments, but you can't negotiate estimates.

* Use multiple estimation techniques, and look for convergence or spread among the results. If these estimates agree and the business target disagrees, *trust the estimates*.

* Use group reviews to improve the estimation accuracy. [Wideband Delphi](https://en.wikipedia.org/wiki/Wideband_delphi) is a structured group-estimation technique that produces very good results.

* For any adjustment you make to the estimates, there should be an assumption written down as part of the requirements.

* A good way to cut down estimates is by looking at the least important features.

* When there are no more features to cut, look at those with the higher estimate and explore ways to reduce the work needed. Make sure you take notes of every assumption you make.

* Make sure you recognize and discuss a mismatch between the project's business target and the project's estimate. This represents valuable risk information that the project might not be successful.

* Always remember that if you torture the data long enough, it will confess to anything. Don't push it.

## Communicating your final estimate
An essential part of providing an estimate is to document the assumptions embodied in it. By doing this, you help to set the expectations that your software project is subject to variability. Assumptions fall into several categories:

* Which features of the overall scope of work are required, therefore included as part of the estimate.

* Which features of the overall scope of work are not required, therefore not included as part of the estimate.

* How elaborate certain features need to be to provide the expected value.

* What is the availability of the key personnel needed to satisfy the estimate.

* What are the dependencies on third-party tools and teams.

* List of major unknowns, influences, and sensitivities of the estimate.

* How good the estimate is, expressed as the uncertainty of hitting it.

* What the estimate can be used for.
