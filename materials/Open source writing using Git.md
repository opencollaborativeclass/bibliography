Being afraid of losing [this blog](http://technikhil.wordpress.com/2012/01/14/open-source-writing-using-git/), I copy and paste it here. If anyone could tell me how I could contact the author please let me know. Thanks. 

Open source writing using Git

Of late I have noticed a trend – writers, especially technical writers, are embracing the software development process and incorporating it into their writing process. There’s a great podcast about this on Herding Code where some technical writers talk about this trend.

Writers are embracing the agile philosophy of software development, one of the core tenets of this is to publish often and get feedback so you can improve/adjust. Authors are posting the content for their book projects online to get feedback – to the extent that publishers like Manning and O’Reilly offer programs that let people access to the book content as soon as the author creates it, for a discounted amount. The pioneers of this practice were the Pragmatic Programmers who offer “beta” versions of their books to customers at discounted prices. The idea behind this of course is that it lets authors get valuable feedback as to what is important, what to focus on. It also provides, authors with an incentive to keep from procrastinating about their writing.

Another major aspect of this trend is the embrace of source control in the writing process. I think this is a great development, and it makes a lot of sense if you think about it.  The book writing process, like software development, is subject to a lot of chopping and changing as the book evolves. Also writing collaboratively on something is I imagine similar to writing code in a team and probably have the same issues –  one needs ways for multiple people to be able to work on the same document without worrying if they are overwriting someone else’s hard work. Finally, a version control provides you with a fine-grained backup that allows you to rewind and replay the evolution of the book, which should be invaluable during the editing process. If there is a conflict somewhere, version control also offers tools to detect and fix it in a safe manner.

Some authors have posted their content on Github, which I think is an awesome idea.    Leveraging, the capabilities of a version control, especially a powerful and distributed one like Git and Github, is well suited for writing projects. Authors can leverage the tools  and capabilities of Github  -

On Github, feedback can easily be provided in the form of  commit notes, line notes, issues – heck you can even fork the project make the corrections and submit a pull request back to the author.
You can use Git as a fine grained distributed backup for your writing project that allows you to rollback specific portions of you project independently.
You can use the social features of Github to collaborate on the project and even drum up interest by distributing the link online.
You can maintain your code samples and other resources separately from your content and correct and upgrade them as needed. This can be very useful if the book is about specific technical frameworks that get upgraded after the book is completed and published.
Github even has a basic editor so you can work on your project online
While browsing through Github for examples of books that use Github as a version control system for writers – I came across this tool which is  in my mind a good first step, but I think there is a lot more that we can do to improve this experience. There are a whole lot of tools being built around this concept which is quite encouraging.

Writing and programming, have a lot in common. Both involve text, both are creative activities and both are ways to express ideas (one to a machine and the other to an audience) . There is scope for a lot of cross pollination of ideas between these fields. I think, currently the main challenge is a lack of knowledge and a fear of the technical nature of a tool like Git.
