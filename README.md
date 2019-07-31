# excel-templates

## Motivation
Let's face it, MS Excel is maybe not the best tool out there (I quite dislike it. I am a python inveterate) but it has some seriously competitive features. It is versatile and a great tool for prototyping. Because of its ubiquity, it has become a great cheap alternative to plenty of activities you want to keep managing seriously up to a reasonably small scale until you find a good solution for scale up.

This is my repo under construction of excel templates that you can use for home, work, non-profit, charity... Enjoy!

## Methodology
In order to manage something, I like to think of all the states by which it can travel, map them and then just take a little note of an event as it comes so I can summarise it in an easy to understand dashboard.

For those who are wondering, I am formally using the concept of [finite state machines](https://en.wikipedia.org/wiki/Finite-state_machine). It is an old concept albeit still incredibly powerful in its ability to clarify what you want to do and why. I am not the only one to think that either. Basically if you are using any kind of [ERP](https://en.wikipedia.org/wiki/Enterprise_resource_planning), you are doing exactly this already, but for a fee.

### Pros of this methodology
* **Simple**: if you size your problem right, you can very efficiently model a wide range of activities with very few states, eg: managing inbound mail could lead to having letters and documents in state of, unopened, reference, unprocessed and garbage. That is 4 states.
* **Comprehensive**: you can "cheat" and add an "other" state and voilà, you have a model that covers absolutely everything. Just mind that if the majority of your states are "other" then you might want to review.
* **Extensible**: if you realise that you are falling in states you did not encounter before, you can easily extend but simply adding a new state. eg: you received many letters but they were in fact destined to your wife, then you can add a "forward" state.
* **Tailored**: You have your own way of working, no problem, you can adapt to anything. The excel templates can be amended to reflect your own workflow very closely.
* **Productive**: after a very brief time modelling, you can be up and running with your new excel sheet and on top of your workflow in minutes.
* **Versatile**: If at one point you need to scale up, it is usually possible to export the log of work you have carried out in the past and upload it into your new tool. The data might need a little massaging before hand.
* **Cheap**: Working like this is the cost of your MS Office license.

### Cons of this methodology
* **Integration**: yes you will have to do all your note taking by hand, which might be a little intense. The benefits of having a program (ERP) is that you can automate different parts of your workflows.
* **Sharing**: your colleague has gone from the office with the document opened and now you can't use it until he closes it.
* **State of the art**: whether you are using a template here or make your own, it is clear you will not be using state of the art tech to manage your work and tasks. If you are a visionary avant-garde (aren't we all!) you could be modelling the workflow of the next 10 years. However chances are that somebody else already solved that problem for you a long time before and you are actually accumulating technological debt.
* **Compatibility**: if you run excel under Windows and somebody else runs it under MacOS, chances are there will  be compatibility issues.

Balancing the Pros and Cons of using MS Excel templates for your work is left to the reader's appreciation. In my view, the pros outweigh the cons if you like to in cycles of model, test then grow.

### Model, test then grow
* TODO

## Contributing
Contributions are welcome!

I was initially thinking of making this repo in an awesome list but realised I could not easily integrate my own file templates. If you have a file, a reference or some documentation you want to contribute, please feel free to send a PR.

If you have a file with an excel macro, please avoid:
* accessing the user's hard drive
* accessing the www
* adding a funky COM automation module that is not from a secure third party
* anything that could be deemed insecure...

These macros and files will be systematically banned.

## License
see [LICENSE](LICENSE.txt)

## Extra Important Information / Disclaimer
For good measure and clarity:

My day job is not antivirus, so although I take utmost care of the quality and safety of the files, I am not liable for any direct or incidental damage occurring from the use of the templates provided here and you implicitly wave any litigation rights by using any files on this repository.

If you want to make sure a file is safe, please scan it with your antivirus software, check the macros inside (open the document with macros disabled first). In case of doubt and in last resort please refrain from using the file.
