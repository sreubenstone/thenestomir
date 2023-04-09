# Learning Tips

#### Instructions

Provide the future generation of learners with a valuable learning tip. Keep it to 3-5 sentences. These learning tips will be printed in _The Nestomir_ book and featured in the native app/e-book.

- Click the pencil icon on the top right of this file to make an edit
- Save your edit (scroll to the bottom of the page)
- The Nestomir™ team will review your submission, and if it looks good, we’ll merge it into the story!

**Tip Example**

> "I once spent 8 hours debugging a file that had nothing wrong with it. I was in such a rush, my brain completely missed I was executing the wrong file name on the command line. The moral of the story: always practice patience when learning a new topic. Your mind will relax and the small details you would ordinarily miss will be absorbed by your brain faster (ultimately speeding up your ability to learn a new topic successfully)." – Steven Reubenstone, New York

## Learning Tips

##### Tip 1

"I once spent 8 hours debugging a file that had nothing wrong with it. I was in such a rush, my brain completely missed I was executing the wrong file name on the command line. The moral of the story: always practice patience when learning a new topic. Your mind will relax and the small details you would ordinarily miss will be absorbed by your brain faster (ultimately speeding up your ability to learn a new topic successfully)." – Steven Reubenstone, New York

##### Tip 2

Being a new programmer in the development field, it is often difficult to figure out things on our own and its perfectly fine. If you are stuck somewhere make sure you ask someone. In the age of internet help is abundant all you need to do is ask. As a new programmer myself, in the initial stages, I used to get too shy and it was scary for me to ask thinking, "What if I asked a really dumb question or what if I look like an idiot". TBH, it does not matter just ask, if a person whom you are asking the question is geniune she/he would definitely help if they laugh, you can always guess the toothpaste they use XD. - Sai Prasad, Bhubaneswar, India.

##### Tip 3

Always try learning by doing - I've seen a lot of people, early stage learners, who mug up the program and then try to write the program from their memory. Remember programming is like an art and is meant to solve a problem. There are 'n' different ways to solve a problem and no two solutions can be exactly similar unless you copy paste it. Take reference from the available resources and try to come up with your own logic and trust me the dopamine shot you get after you see your logic working, nothing in the world can match that for sure. You can always start off with some very simple but annoying problem from your daily life to come up with small program. For example I used to stick with my computer till late night and sleep while working on it but the computer used to run for all night. I needed a program where I could just schedule a time and make the computer shutdown with a prompt before shutting down, just in case I'm still awake. So to achieve this I wrote a small program in Java and Swing. It was really fun and I use it till now. I wrote the program in 2016. - Sai Prasad, India.

##### Tip 4

Take advantage of new AI technologies that can mentor you through your learning experience. For example, I wrote a simple program in Java that used a Scanner object x to collect user input at the console and assign it to different variables. When compiled, it worked for the first variable assignment, and the second, but not the third. Strange. So I asked ChatGPT what I was doing wrong after verifying there was nothing wrong with my code.

  Me: Hi, can you help me with a Java problem?

  ChatGPT: Sure, what's the problem you're having?

  Me: I'm trying to use Scanner methods to read input from the user at the console, but when I use nextDouble() followed by nextLine(), the nextLine() method seems to be skipped over. Can you help me figure out why?

  ChatGPT: Yes, that's a common issue with the Scanner class. When you use nextDouble(), it only reads the double value, but it leaves the newline character (\n) in the input buffer. When you then call nextLine(), it reads that newline character, which gives the appearance that the nextLine() method is being skipped over.

  Me: That's really strange. Is there any way to fix this issue?

  ChatGPT: Yes, you can call the nextLine() method after nextDouble() to consume the newline character. Here's an example:

        Scanner input = new Scanner(System.in);
        System.out.print("Enter a double: ");
        double myDouble = input.nextDouble();
        input.nextLine(); // consume the newline character (note: I added this and it fixed my problem, AND I understood WHY this was happening!!)
        System.out.print("Enter a string: ");
        String myString = input.nextLine();

  Me: Ah, I see. That makes sense. Thanks for your help!
