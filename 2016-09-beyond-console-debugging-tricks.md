I don’t consider myself a nitpicker. That’s only true, and it’s all fine and dandy… until I find a console.log() that someone forgot to remove from the JavaScript code. And if we’re talking about debugger statements… all hell breaks loose! People I have worked with already know how much that bugs me (pun intended).

我不认为自己是个吹毛求疵的人。{todo} 直到我发现有人忘记从Javascript代码中删掉的console.log()。如果我们在谈论调试语句的话...一堆破坏性的东西就会迸发出来！ 和我一起工作过的人早已知道那些语句有多么地困扰我（原文bugs me - 双关语）。

Sure, I had a few slips of the mind in the past. Who hasn’t? I learned quickly, though. Using those statements should be a last resource, especially when you are working with big teams. It’s disrespectful to your teammates to leave them in the code!

当然，过去我是会有些这样的想法（个人认为是在代码里使用调试语句的想法）。谁又不是呢？不过，我很快就学会了。那些语句应该作为最后的稻草，尤其是你和大团队一起工作时候。把这些语句留在代码里是对你的同事的不尊敬。

So that is why I started avoiding console.log() like the plague, and I can’t remember the last time I used a debugger statement. It’s been years now! I saw the light!

所以，这就是为什么我开始像躲瘟疫一样不去使用console.log()了， 而且我都记得不最后一次使用调试语句是什么时候了。 到目前为止已经好多年了！我那时就顿悟了！

My experience at OutSystems, while meeting with clients and interacting with other developers, has shown me that people will do some crazy stuff for the sake of debugging. Some of this stuff is so out there and time consuming, that I can’t even understand their reasoning.

我在OutSystems的工作经验，和客户会面以及同其他开发人员打交道，告诉我人们为了调试会做出一些非常疯狂的事情出来。其中一些就出现在那里，而且还特耗时，我甚至都不明白为什么。

Instead of investing a little time, researching better ways and finding the right tools for the job, some people find extremely complicated schemes that end up not helping at all.

一些人没有花时间去搜寻更好的方法和正确工具来做这工作，而是找到非常复杂的方案，这些方案最终却一点忙也帮不上。

Inspired by those people and the inexplicable juggling I saw them doing while trying to debug stuff, I collected some of the most common examples I can present as proper alternatives for that process. With these simple examples you will learn how to avoid the wrath of your colleagues. You know, the prickly ones that get extremely bugged when you leave those debuggers on that JavaScript file.

