# week8-project
What you'll be doing!

Remember the focus is React so take as much time as you need reading articles, watching videos doing online tutorials before rushing into things. React docs are good so jsut check their website and lots of resources all over online. 

Past react workshop resources section :  https://github.com/foundersandcoders/begin_react_workshop#resources


## Reusable Components

React is all about components and the best ones are reusable. Not only should you make your components as reusable as possible inside your own apps but if you feel that the react community would benefit from your hardwork then publish it and gain fame. 

I did just that https://github.com/JackDanielsAndCode/react-native-multi-slider on github
and https://www.npmjs.com/package/react-native-multi-slider on npm

I peaked at 90 downloads in one day. Now I get 2 per day as people realised how bad it was... But I have 7 random starGazers on the repo and some randomer even made a pull request to add a feature to the functionality and another randomer has a request for another feature. These randomers now depend on this slider in their projects and it feels good to be contributing to the open source community (I get that fuzzy feeling inside).

read the code with a pinch of salt as written for react native! Much better to look for simple components and adopt best practises.




## What makes a good reusable component

Something that is simple, easily customisable and well written! 

Something that can't demonstrate itself quickly will be quickly looked over. Concentrate on doing one thing well do indeed add more features but don't try and be a map, a sandwich, a photoalbum all together, split it out into components. The clearest example of this is facebook releasing a messenger and facebook app for phones. Both do their job well.

Don't make it too specific to just your needs. If you can think of a way to simply extend part of it to allow for multiple use cases do. At the same time you can't accomodate all just try make it easy to configure allowing them to pass in options (props?) and if not resorting to defaults.

Good code will allow the person to fully understand whats going on inside your component and understnad how it can be used. Also they may want to modify it for their particular use case and would like to make just minor additions rather than rewrite it all because they can't understand whats going on.

Don't cause unnecessary side effects for the rest of their project. You're component should focus on itself solely and not the outside world.

Keep up to date with changing software, make sure your component is as compatitible with different versions as possible and if not define its limitations.


## Show case a reusable Component 

Good docs and pics of your component will instantly attract a user. You will publish to npm but also there is a website called http://react-components.com/ which shows all the react components. Check it out and check here and on giithub to see examples of other peoples work.

Here is a little article on publishing a react component to npm. http://chadly.net/2015/04/publishing-react-to-npm/
You may want to look at best practises. And you shoudl investigate teh best practises to publishing on npm in general (semver etc).

## Good Luck 

think of something original, silly, useful, fun, creative, inspiring... make it a module. You have 3 days, so focus on learning react and writing quality code that someone will actually want to use as opposed to taking on more than you can chew and having a half working app. Mine was just a slider... Yours could be a little clock display, calculator, burger menu, note pad, talking duck...

http://material-ui.com/#/components/appbar is an example of a package of components that look really cool

