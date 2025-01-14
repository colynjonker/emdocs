<div class="ez-academy">
	<div class="ez-academy__body">
		<main class="micro-learning">
		<ul class="doc-nav">
			<li class="doc-nav__item"><a href="../../docs/microlearning/crashcourse-api-gateway-index" class="doc-nav__link">Home</a></li>
			<li class="doc-nav__item"><a href="#intro" class="doc-nav__link">Intro</a></li>
			<li class="doc-nav__item"><a href="#theory" class="doc-nav__link">Theory</a></li>
			<li class="doc-nav__item"><a href="#practice" class="doc-nav__link">Practice</a></li>
			<li class="doc-nav__item"><a href="#solution" class="doc-nav__link">Solution</a></li>
		</ul>

<div class="doc">

##### Intro

# Setting up entry gate

In this microlearning, we will focus on setting up the entry gate for the API Gateway.
This entry gate will host the endpoints that will be made available to external parties so they can call these endpoints to obtain access to certain backend operations (if authorized)

Should you have any questions, please contact academy@emagiz.com.

- Last update: February 11th, 2021
- Required reading time: 3 minutes

## 1. Prerequisites
- Basic knowledge of the eMagiz platform

## 2. Key concepts
This microlearning centers around setting up the entry gate for the API Gateway solution of eMagiz.
With entry gate, we mean: The piece of functionality that hosts all endpoints and is responsible for checking the authentication and routing messages to the correct backend operation
With API Gateway we mean: A collection of RESTful API operations that can be published to the outside world to give them access to applications that are linked to your business process

The entry gate is created by eMagiz without the need of any user making manual changes to the entry gate. This accelerates the building of an API Gateway solution a lot.

##### Theory

## 3. Setting up entry gate

The central part where all data traffic is coming in is called the entry gate when we talk about the API Gateway. 
This entry gate is responsible for hosting all designed endpoints that have been transferred to Create.

The first time you transfer an API integration to Create eMagiz will create the entry gate for you. You as a user do not have to do one single thing. Easy right.

Furthermore, every time you add a new API integration to Create eMagiz will automatically update all entry gate to ensure that this newest operation can be accessed by external parties.

In case you have made changes to existing operations you will have to use the Reset flow option to ensure that the latest changes are indeed actualized in the entry gate. 
This can be done without harm as eMagiz has standardized the entry gate for you and you don't have to make changes manually.

##### Practice

## 4. Assignment

Add a new API integration to Create and see how eMagiz (re)creates the all entry flow for you.
This assignment can be completed with the help of the (Academy) project that you have created/used in the previous assignment.

## 5. Key takeaways

- The entry gate is the central part where all data traffic is coming in
- eMagiz will automatically build the all entry for you
- No manual changes are necessary

##### Solution

## 6. Suggested Additional Readings

If you are interested in this topic and want more information on it please read the help text provided by eMagiz.

## 7. Silent demonstration video

This video demonstrates how you could have handled the assignment and gives you some context on what you have just learned. Disclaimer, you only see the eMagiz part but if you follow the above steps you are good to go!

<iframe width="1280" height="720" src="../../vid/microlearning/crashcourse-api-gateway-setting-up-entry-gate.mp4" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

</div>
</main>
</div>
</div>