# Exercise 3: Parameter Experimentation
**SObjective: Understand how parameters affect output diversity.**

Use the same prompt with temperature = 0.2 and then with temperature = 0.9.

Repeat with different top-p values (e.g., 0.5 vs 1).

Record how the style, randomness, and focus of responses change.

-----
**First prompt:Tell me about cloud computing.**

Its response: for 0.2 temperature and top-p value of 0.5.

    At its simplest, cloud computing is the delivery of computing services—including servers, storage, databases, networking, software, and analytics—over the internet (“the cloud”).

    Instead of owning and maintaining physical data centers and hard drives, you access technology resources from providers like Amazon, Microsoft, or Google on an as-needed basis.

    1. The "Utility" Analogy
        Think of cloud computing like the electricity grid in your home:
        Traditional Computing: Like owning a noisy, expensive generator in your backyard. You have to buy it, fuel it, and fix it if it breaks. If you need more power, you have to buy a second generator.
        Cloud Computing: Like plugging a toaster into a wall outlet. You don't care where the power comes from or how the power plant works; you just use what you need and pay only for what you consume.

    2. The Three Main Service Models
        Cloud computing is generally categorized into three "layers":
        IaaS (Infrastructure as a Service): This is the foundation. You rent the "raw materials"—virtual servers, storage, and networks. You are responsible for the operating system and applications.
        Example: Amazon Web Services (AWS) EC2, Microsoft Azure.
        PaaS (Platform as a Service): This provides a framework for developers. It includes the operating system and tools needed to build and host apps, so developers don't have to worry about managing the underlying hardware.
        Example: Google App Engine, Heroku.
        SaaS (Software as a Service): This is the most common for everyday users. You access a finished functional application via a web browser or app. The provider manages everything.
        Example: Gmail, Netflix, Dropbox, Salesforce, Microsoft 365.

    3. Types of Cloud Deployment
        Public Cloud: Resources are owned and operated by a third-party provider and shared with other organizations (like an apartment building).
        Private Cloud: Resources are used exclusively by one organization. It can be physically located on-site or hosted by a provider (like a private house).
        Hybrid Cloud: A mix of both. A company might keep sensitive data on a private cloud but use the public cloud for high-traffic web applications.

    4. Key Benefits
        Cost: You eliminate the "capital expense" of buying hardware and software. You pay a monthly subscription or a "pay-as-you-go" fee.
        Scalability: If your website suddenly gets a million hits, you can instantly add more "power." When the traffic drops, you can scale back down to save money.
        Speed: You can deploy complex global technology environments in minutes rather than weeks.
        Reliability: Cloud providers mirror your data across multiple locations, making data backup and disaster recovery much easier.
        Security: Major cloud providers invest billions in security, often providing better protection than a small or medium-sized business could afford on its own.

    5. Who are the "Big Three"?
        The market is dominated by three major players:
        Amazon Web Services (AWS): The pioneer and current market leader.
        Microsoft Azure: Very popular with large corporations already using Microsoft software.
        Google Cloud Platform (GCP): Known for its strength in data analytics and artificial intelligence.
        Summary
        Cloud computing has changed the world because it democratized technology. A teenager in a garage now has access to the same massive computing power as a Fortune 500 company, allowing for faster innovation and lower costs for everyone.

---
**Second prompt: If I were a beginner, explain cloud computing.**

It's response for 0.2 temperature and top-p value of 0.5:

    If you are a total beginner, the easiest way to understand cloud computing is this:

    Cloud computing is using someone else’s computer to do your work, instead of using your own.

    Here is a breakdown of how that works in real life:

    1. The "Hard Drive" vs. "The Cloud"

        The Old Way: If you wanted to save a photo, you saved it onto your computer’s hard drive or a thumb drive. If you lost that thumb drive, the photo was gone forever.
        The Cloud Way: You upload the photo to the internet (to a service like Google Photos or iCloud). The photo is actually sitting on a giant, powerful computer in a high-security building owned by Google or Apple. Now, you can see that photo from your phone, your laptop, or your friend’s tablet just by logging in.

    2. A Simple Analogy: The Pizza Shop

        Imagine you want to eat pizza. You have two choices:
        The "Non-Cloud" Way (Owning your own hardware): You build a pizza oven in your kitchen, buy the flour, grow the tomatoes, and make the cheese. It’s expensive to set up, and if you only want pizza once a month, that oven is just taking up space and costing you money.
        The "Cloud" Way: You go to a pizza shop. They have the ovens, the ingredients, and the chefs. You just pay for the slice you eat. If you want 50 pizzas for a party, they can handle it. If you want zero pizzas next week, you don't pay anything.
        Cloud computing is the "Pizza Shop" for technology. You "rent" the computer power you need, when you need it.

    3. You are already using the Cloud!

        You probably use the cloud every single day without realizing it:
        Netflix: You aren't "downloading" a whole movie file to your computer's hard drive. You are "streaming" it from Netflix’s cloud.
        Gmail/Outlook: Your emails aren't stored on your computer; they live on Google’s or Microsoft’s servers.
        Spotify: You have access to millions of songs without needing to own a single CD or digital file. The music lives in the cloud.

    4. Why is it called a "Cloud"?

        It’s not actually in the sky! It’s called a cloud because, in the early days of the internet, engineers would draw diagrams of networks. When they got to the part of the internet they didn't control, they would just draw a cloud shape to represent "the stuff happening somewhere else." The name stuck.
        In reality, the "Cloud" is just thousands of massive buildings (called Data Centers) filled with millions of humming computers and cables.

    5. Why is it a big deal?

    It’s Cheaper: You don't have to buy expensive computers. You just pay a small monthly fee (like Netflix) or pay for what you use.
    It’s Safer: If you spill coffee on your laptop and it dies, your "cloud" files (like your Facebook photos or Google Docs) are perfectly safe.

    It’s Everywhere: As long as you have an internet connection, you can access your "stuff" from anywhere in the world.

    Summary for a beginner:
    The Cloud is just the internet acting as a giant hard drive and a giant brain that you can plug into whenever you need it.

---
**Second prompt: Here are the five main benefits of cloud computing:**

Summarize the main benefits of cloud computing in five bulet points.

    Cost Savings: You don’t have to buy expensive hardware or servers upfront; instead, you pay a subscription or a "pay-as-you-go" fee for only what you use.

    Accessibility: You can access your files, photos, and applications from any device (phone, tablet, or laptop) anywhere in the world with an internet connection.

    Scalability: You can instantly increase or decrease your storage and "computing power" as your needs change, much like turning a water faucet up or down.

    Reliability and Recovery: Because your data is stored in multiple professional locations, it remains safe and easy to recover even if you lose your phone or spill coffee on your laptop

    Automatic Updates: The cloud provider handles all the boring technical maintenance and security patches, so you always have the latest and most secure version of the software without doing any work.

---
**What I observed in style, randomness, and focus of responses change.**

    With temperature set to 0.2 and top-p at 0.5, the responses were highly structured, predictable, and focused. The language was formal and instructional, with minimal creative deviation. Randomness was low, and the outputs consistently followed standard explanatory patterns. The answers stayed tightly aligned with the prompt and avoided digressions. This configuration produces stable, deterministic, and clarity-focused responses.