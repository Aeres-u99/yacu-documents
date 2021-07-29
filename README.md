### Yacu

##### Guideline

* Should be usable on cli 

* Should allow passing from PIPE

##### Planning

We are basically supposed to push anything thats sent to Telegram and a Metadata regarding the same to Another Channel

For inital state we will implement it using basic tg bot, which will simply set the filesize limit to 20mb. Its just fine but it should work

The problem happens when we are supposed to retrieve it, for retrieval if its to be done via web, we will have to host a server. Mostly if the file size is 20mb (max) then doing this is easy (relatively easy) as even with small filesize we will be just fine. 

But otherway around would be difficult, can we retrieve data directly from tg without relying on browser? Thats a good question. 




