---
layout: post
title: Documentation is sexier than you think
---
TL;DR - Documentation indirectly improves the user experience by improving the developer experience. Sexy, I know.

Creating your very first page on the Internet is extremely exciting. Something happens inside you after navigating to your own URL, you refresh the page and the text "Hello World" changes to "Hi Mom! I'm on the Internet!" The rush is remarkably satisfying. After you make a number of websites for your friends, your family and that organization that actually paid you some money, you tend to have fewer and fewer moments that are as exciting as creating your first page. They still happen, just less frequently and usually when you least expect it. I was recently surprised to experience one of these rewarding moments and I plan to hold on to this feeling as long as I can. 

Prior to starting Bloc, a remote coding bootcamp, I had worked in a number of content management systems with some teammates in my office, others across the US and a few 12 time zones away. One particular CMS we used didn't fully track the changes made by each user. We kept very detailed notes in a project management tool and we had solid review processes. From time to time, the unfortunate miscue still happened. We would scramble to fix the issue, do our best to update our process and then inform the entire team of how and why the miscue happened so it could be avoided in the future. It seemed like there was a disconnect between the work we had created in the CMS and our detailed notes.

During my studies with Bloc, I read about "Documentation" within my files. Yes, I understood that you could create comments. 

{% highlight js %}
// useful for saying anything you'd like, however you'd like
{% endhighlight %}

It wasn't until I started writing comments for the real functions and attributes that I had written that it hit me. There's a framework for describing code within the code and many, many developers follow this framework.

{% highlight js %}
/*
* @function nameOfTheFunction
* @desc What the function does
* @param {Object} what item(s) are passed in, if anything at all
* @return {Number} what gets returned, if anything at all
*/
var describingThings = function() {
    ....
    };
{% endhighlight %}

Wait, lots of devolopers do this?? In a moment, all my past failures that could have been avoided flashed before me:

<ul>
    <li>Any developer can jump in and quickly understand what the original developer intended.</li>
    <li>If the original developer wants to go on vacation, they can!</li>
    <li>If the original developer feels a little sick, they can stay home and feel confident in their team to understand the code.</li>
    <li>This means fewer lengthy and disorganized meetings. We're developers after all, we want to make things, not talk about making things.</li>
    <li>A newly hired developer can begin to understand how their new coworkers think and work.</li>
    <li>Developers can take their full parental leave and know they'll be able to catch up when they return to work.</li>
</ul>

Ok, maybe documentation won't be able to completely fulfill each of these points but, it certainly helps developers and their team to better understand the problem they're trying to solve.

Documentation is a simple action a developer can take to reduce a huge amount of future pressure on other developers leaving us to do what we do best - solve problems for users and make more things.