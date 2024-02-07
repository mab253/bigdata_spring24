# HDFS/GFS: in-class exercise 🧱🧊

<img width="601" alt="Screenshot 2024-02-07 at 2 20 38 PM" src="https://github.com/mab253/bigdata_spring24/assets/17707843/6827ec01-67a5-4636-8bf3-038dc963a8ea">

We will divide into groups to work on illustrating distributed file systems. Let's start with 🐘 **Hadoop** ...

Every group has a collection of **legos**, and 4 pieces of paper.
- Each colorful lego block represents a different **file**: you should have a blue file, a yellow file, and an orange file.
- The lego blocks that are 4x2 = **1 block** each, we are going to say **64MB** in this version.
- There is 1 file that takes up 2 blocks: for some groups this is yellow, for some groups this is blue. You should see these labeled in marker with "1" and "2," for the 2 blocks that make up the file. 
- (The brown long pieces are just to hold the blocks together.)
- The small red piece is just for you to illustrate and point out parts of the system with your group.

Once you see which blocks you have, go through the following steps as a group! Check in with each other, and make sure you understand each step of the distributed system as it goes.

1. Set up your **nodes** with your 4 pieces of paper. What names do these have? (Remember we are starting with Hadoop nomenclature). Label each datanode with a number, 1-3.
2. **WRITE** the file that is 1 block long (either blue or yellow) to the system. Where do the blocks go? How many blocks are involved? Which part of the system initiates the steps?
3. **WRITE** the file that is 2 blocks long (either blue or yellow) to the system. Where do the blocks go? How many blocks are involved? Which part of the system initiates the steps?
4. **WRITE** the orange file into the system. The orange file is smaller! (It is only 1 of the orange pieces, 1x2) Where do the blocks go? etc.
5. Imagine you have a client that wants to **READ** the 2-block file. What are the steps to make this happen? Which node calls what? Be very specific!
6. Now imagine the same client wants to **APPEND** another chunk of data to the orange file. What are the steps to make this happen? Be very specific!
7. Now: o no, Node #2 has failed! The same client still wants to **READ** the 2 block file again. How does this happen? What else happens?
8. Disaster: your entire cluster fails! All nodes are offline! What happens now? Be as specific as you can.

Go through the following questions with your group - make sure you understand collectively! And make note of any questions you have, so we can clear it up when we come back as a larger group.
1. What information does the **namenode** store?
2. What kind of node does the **client** directly read data from?
3. What does the namenode remember if the whole cluster shuts down?
4. Can I re-write portions of my data on the DFS?
5. What are some key limiting factors in the scalability of this system?
6. How big is the file that takes up 2 full blocks?
7. How big is that smaller orange file? (If the yellow blocks = 64MB?) How much space does it take up in the DFS?
8. Where does the name of Hadoop come from?

Also check your group's understanding of the following terms and how they relate to the system:
- client
- replication factor
- block
- rack awareness
- batch processing
- heartbeat monitoring

We will then circle back as a larger group to discuss! And draw.
