---
title: Filing bugs and feedback
description: Help us make Windows Mixed Reality better by filing feedback using the correct categories in the Feedback Hub app.
ms.topic: article
keywords: Windows Mixed Reality, Mixed Reality, Virtual Reality, VR, MR, Feedback, Feedback Hub, bugs
---



# Filing bugs and feedback

## Why it's important

The engineering team uses the same mechanism internally for tracking and fixing bugs, so please us Feedback Hub and report any bugs you are seeing; we are listening!

## Before you file feedback

Please make sure your PC is set to provide us with full data for feedback and diagnostics. Here's how to double check the setting on your PC before filing feedback:
1. Open the Windows **Settings** app.
2. Click on **Privacy**.
3. Go to **Feedback & diagnostics** on the left pane (note that this has been renamed to **Diagnotics & feedback** in recent Windows Insider builds of Windows.
4. Under **Select how much data you send to Microsoft**, select **Full** if it isn't already selected.
5. Be sure to restart your PC and repeat the steps to reproduce your issue before filing feedback.

## How to file feedback for Windows Mixed Reality immersive headsets on PC
1. Ensure you have the immersive headset connected to your PC.
2. Launch **Feedback Hub** on desktop with the HMD connected.
3. Go to **Feedback Tab** on the left pane. ![Feedback Tab](images/feedback1.png) 
4. Click **Add new feedback** button to enter the feedback. ![Add new feedback](images/feedback2.png)
5. Select **Problem** in **What kind of feedback is this?** to make the feedback actionable. ![Details and repro steps](images/feedback3.png)
6. Provide meaningful feedback title in **Summarize your issue** box.
7. Provide details and steps to reproduce the issue in the **Give us more detail** box.
8. Select **Mixed Reality** as the top category and then pick an applicable sub category:

   | Subcategory      | Description                                                                           |
   |------------------|---------------------------------------------------------------------------------------|
   | Apps             | Issues with a specific application.                                                   |
   | Developer        | Issues in authoring / running an app for Mixed Reality.                               |
   | Device           | Issues with the HMD itself.                                                           |
   | Home experience  | Issues with your VR environment: interactions with the Windows Mixed Reality Home.    |
   | Input            | Issues with input methods: motion controllers, speech, gamepad, or mouse and keyboard.|
   | Set up           | Anything that is preventing you from setting up the device.                           |
   | All other issues | Anything else.                                                                        |


9. To help us identify and fix the bug faster, capturing traces and video is extremely helpful. To start collecting traces, click on **Start capture**. This will begin collecting traces and a video capture of your mixed reality scenario.![Start Capture](images/feedback4.png)
10. Leave the Feedback app and run through the broken scenario. Do not close the Feedback Hub app at this point.
11. After you are done with your scenario, go back to the feedback app and click **Stop Capture**. Once you do that, you should see that a file containing the traces has been added.
12. Click **Submit**.![Submit](images/feedback5.png)

This will lead you to the "Thank You" page. At this point, your feedback has been successfully submitted. 

After you submit feedback, to easily direct other people (e.g. co-workers, Microsoft staff, [forum](https://forums.hololens.com/) readers, etc.) to the issue go to **Feedback > My Feedback**, click on the issue, and use the **Share** icon to get a shortened URL you can give to others to upvote, or escalate.

> [!IMPORTANT]
> Before filing a bug, please ensure you meet the following constraints so that the logs are successfully uploaded with the feedback.
>    * Have a minimum of 3GB free disk space available on the main drive of the device.
>    * Ensure that a non-metered network is available in order to upload cabs.


## See also
* [Troubleshooting](troubleshooting-windows-mixed-reality.md)

