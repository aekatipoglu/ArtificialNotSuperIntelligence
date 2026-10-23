# ArtificialNotSuperIntelligence
I think LLMs are great, but we also need human-like AI. I believe the path forward lies in neuromorphic systems.

At the beginning of this year (2026), I spent some time researching how AI systems could be designed to better mimic the way the human brain works. I certainly didn't grasp such a complex structure in all its depth, but I did learn a great deal about how neurons and other components in the brain function. 

Ultimately, my conclusion was that if we didn’t waste time trying to replicate certain parts of the brain and instead replaced others with different methods, we might be able to create a proof-of-concept (PoC) for a neuromorphic intelligence organ that can hear, understand, and speak. There’s a theory called the motor theory of speech. According to this theory, when we hear and understand the person across from us, we mentally simulate the movements involved in producing that sound. I suspect that meaning exists as an abstract representation between these input and output movements. If we ourselves convey meaning internally and externally in this way, it makes perfect sense to implement this in the model as well. 

Then I looked into vocal tract systems. I evaluated “[Pink Trombone](https://dood.al/pinktrombone)”, a lightweight program capable of real-time processing, developed by Neil Thapen. It didn’t require many parameters, and since the parameters were continuously variable, it was a model that perfectly suited my needs. I also thought that it might be possible to train a lightweight, real-time ear model using synthetic data generated with Pink Trombone. However, I didn’t have the knowledge to develop this ear model, so I put it off until a day when my technical skills would be sufficient. 

A few days ago, I wanted to look into this project again. That’s when I discovered the [Samuel](https://github.com/vvolhejn/samuel) project developed by Václav Volhejn. It was exactly what I wanted, created by an expert in the field. We now have a mouth and ear system that provides exactly the same type of input and output. 

I still lack the technical expertise to work on the brain, but I’ve come to realize that even if I wait, technology keeps advancing without waiting for me. I want to work on a project that I enjoy, without worrying about success.

## What Are We Pursuing?

We are pursuing human-like intelligence. Therefore, comparing human intelligence itself with the options we have at our disposal will first point us in the right direction. I don’t think there’s a need to discuss the difference between classical computers and human intelligence; let’s move directly to LLMs.

| | Human Intelligence | Mainstream LLM |
| :--- | :--- | :--- |
| **Input-Output** | Very slow. | Very fast. |
| **Learning Method** | Can learn to speak simply by interacting with parents. | A zillion words are crammed into its head. |
| **Continuous Learning** | The knowledge it acquires is etched into the brain's synaptic weights and directly shapes its character. | It doesn’t actually acquire knowledge; it retains as much of its past information as fits within its context window. If that’s not enough, it uses RAG to take notes and re-read them every time, thanks to its speed. |
| **Collaboration** | Due to input-output speeds, communication is a bottleneck. | Again, thanks to their speed, a group of LLMs can achieve incredibly complex tasks in a short time through great collaboration based on their respective areas of expertise. |
| **Motivation** | There are hardcoded structures in the brain that guide its intelligence; maybe “it also needs drives and emotions.” | It has no motivation. |

Wait—are LLMs actually much more functional!? So, what kind of picture would emerge if LLM systems—which typically bypass their weaknesses compared to humans through sheer input-output speed—were to operate at the exact same speed as humans? If we could properly model the human brain—which currently lags behind due to the cellular speed limits of human biology—and implement it in semiconductors, so that, with all the advantages of human intelligence, it could perceive the world at human speed whenever it wanted, and at other times function like humans who have been greatly accelerated through time dilation in a digital universe, what would that look like? Our goal is human-like intelligence. Neuromorphic processors like Intel Loihi are currently being developed, but since GPUs are the most advanced and accessible hardware we have at our disposal, we plan to build our Proof of Concept (PoC) targeting GPUs.

## Contributing

Building a system at the intersection of biological cognition and machine intelligence naturally calls for diverse perspectives.

Whether your background is in **engineering, neuroscience, biology, psychology, linguistics**, or you simply share a deep interest in exploring human-like intelligence, your contributions are welcome.

Feel free to open a **Discussion / Issue** to share insights, suggest relevant research, critique architectural choices, or submit a **Pull Request**.

## Credits

This project builds upon the work of:

* **Neil Thapen** — Creator of the original [Pink Trombone](https://dood.al/pinktrombone/) physical vocal tract synthesizer.
* **Zack Qattan** — Creator of the programmable version of [Pink Trombone](https://github.com/zakaton/Pink-Trombone).
* **Václav Volhejn** — Creator of [Samuel](https://github.com/vvolhejn/samuel), a model that learns to control Pink Trombone to mimic speech.
