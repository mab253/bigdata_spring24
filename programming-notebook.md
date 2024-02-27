# 🤖 Spark Programming Assignment 

**due: March 8, 11:59pm** - 

For this assignment, you will need to:
- finish the Codecademy course! take a screenshot of the **My Profile** page so that it shows your name, and the 100% completion of the Intro to Big Data With PySpark course, something like this:
<img width="600" alt="Screenshot 2024-02-26 at 10 50 12 PM" src="https://github.com/mab253/bigdata_spring24/assets/17707843/8dc1c8b3-1610-4d39-988e-8bc27fb19a8d"> 
<p>&nbsp;</p>

- next, you will need a free Databricks account to work on the Spark notebook on a cluster. 
- sign up for **Databricks Community Edition** [here](https://docs.databricks.com/en/getting-started/community-edition.html). Make sure you follow the instructions carefully on that page, so that you sign up for the forever-free, community version.
- When signing back into Databricks after creating your account, you may have to check for a link at the **bottom** of the page, to make sure you are signing in for the **Community Edition**:
<img width="600" alt="Screenshot 2024-02-26 at 5 09 07 PM" src="https://github.com/mab253/bigdata_spring24/assets/17707843/9ecfa8d0-d9a9-44b4-b9d3-2437b662f9c6">
<p>&nbsp;</p>

- 💥**IMPORTANT!** before you get started with notebooks, you need to enable the DBFS (distributed file system) in your Databricks account. Follow the instructions to adjust the **Admin Settings** and **enable DBFS** [here](https://docs.databricks.com/en/administration-guide/workspace-settings/dbfs-browser.html).
- After you have enabled DBFS, you'll need to start a cluster. Check out the video [here](https://www.youtube.com/watch?v=csa3Wz5xt5k) (1min.) for instructions. You can choose basic defaults for any of the options.
- After you have a cluster, go back to your dashboard in Databricks. Find the sidebar menu to the left, hover over it until you see **Workspace** with the little notebook icon, and click that open. Find where it says "**Users**," and you should see your own e-mail address.
- Find the arrow to open a menu near your e-mail address - you should see an option to **Import.** Click that!
<img width="600" alt="Screenshot 2024-02-26 at 11 07 25 PM" src="https://github.com/mab253/bigdata_spring24/assets/17707843/c519ffae-e9d0-4df7-a8ba-e5a1c2c6fa38">
<p>&nbsp;</p>

- In the box that pops up for Importing, paste the following URL: https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/4500837298146969/604655822718511/140076126772634/latest.html
- You should now finally see a notebook! Very similar to a Jupyter notebook at first glance.
- Check out the settings in the upper right - it should automatically connect you to your hardware cluster, but you may need to tell it to **Connect.** Look at your cluster size, how many cores you have, etc. but checking out the Cluster **Configuration** from the menu in the upper right.
- Databricks notebooks come with Spark installed! Look at **View -> Spark UI** and get familiar with the Spark user interface. Check out the different tabs and pages available there. (Remember, this is where you can ultimately see DAG visualizations, timelines of tasks, error logs, and other performance metrics.)
- When you are ready, go through the cells in the notebook, writing either Python code or text, depending on what each cell asks you to do.
- You may want to consult the Codecademy course - most questions were directly covered there!
- This is not an exam (it's open book), and you are allowed to ask questions about the assignment on Discord. (Either I can help there, or ideally your fellow classmates.) Please make sure that your final work is your own code and words, and you will be asked to cite the sources you used at the end of the notebook.
- Happy coding!

- **NOTE:** if you save your work and come back to it later, you will find that your cluster session has "Terminated." That's fine! You will need to **Create a new resource** in the dropdown menu at the top right of the notebook, where your cluster information lives. There is no limit to how many times you can create new clusters, and you may need to do this in the middle of a work session. Should be no problem!
