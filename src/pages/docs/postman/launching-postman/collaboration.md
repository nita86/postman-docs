---
title: "Collaboration"
order: 10
page_id: "collaboration"
warning: false
contextual_links:
  - type: section
    name: "Additional Resources"
  - type: subtitle
    name: "Videos"
  - type: link
    name: "Team collaboration with Postman"
    url: "https://www.youtube.com/watch?v=8tLvvQ-3Nx0"
  - type: link
    name: "Scaling Team Collaboration at Atlassian"
    url : https://www.youtube.com/watch?v=wYBZrdukack

---
Postman allows all users to collaborate with their teams through Team Workspaces. Using this feature, you can easily collaborate and share your collections, environments, integrations, history, mocks, monitors, and more.

> Free collaboration is available in version 6.2 and above.

## Contents

* [Working with team workspaces](/docs/postman/launching-postman/collaboration/#working-with-team-workspaces)

    * [Inviting a team member to a personal workspace](/docs/postman/launching-postman/collaboration/#inviting-a-team-member-to-a-personal-workspace)

    * [Creating a new workspace](/docs/postman/launching-postman/collaboration/#creating-a-new-workspace-from-the-menu)

* [Team discovery](/docs/postman/launching-postman/collaboration/#team-discovery)

    * [Making your team discoverable](/docs/postman/launching-postman/collaboration/#making-your-team-discoverable)

    * [Finding teams within your organization](/docs/postman/launching-postman/collaboration/#finding-teams-within-your-organization)

* [Usage limits for free users](/docs/postman/launching-postman/collaboration/#usage-limit-for-free-users)

    * [Usage limit](/docs/postman/launching-postman/collaboration/#usage-limit)

    * [How archiving works](/docs/postman/launching-postman/collaboration/#how-archiving-works)

    * [Recovering archived collections](/docs/postman/launching-postman/collaboration/#recovering-your-archived-collections)

* [Next steps](/docs/postman/launching-postman/collaboration/#next-steps)

## Working with team workspaces

Create a Team Workspace by inviting a team member to join a personal workspace or create one using the app or web dashboard.

### Inviting a team member to a personal workspace

In the app, select **Invite**.

[![invite button](https://assets.postman.com/postman-docs/Screen Shot 2019-11-11 at 5.21.17 PM.png)](https://assets.postman.com/postman-docs/Screen Shot 2019-11-11 at 5.21.17 PM.png)

Enter the email address of the individual you’d like to invite to your team workspace, click **Add** > **Invite to team**.

[![invite team member](https://assets.postman.com/postman-docs/Screen Shot 2019-11-11 at 5.21.45 PM.png)](https://assets.postman.com/postman-docs/Screen Shot 2019-11-11 at 5.21.45 PM.png)

The individual will be added to the team once they accept their invitation.

> "My Workspace" is a default workspace created by Postman. This workspace is different from other personal workspaces as it cannot be shared with anyone. When you invite a teammate to join another personal workspace, Postman converts it into a team workspace.  

### Creating a new workspace from the menu

Select your current workspace in the app to open the workspace menu, then click **Create New**.

[![create workspace](https://assets.postman.com/postman-docs/Screen Shot 2019-11-11 at 5.29.42 PM.png)](https://assets.postman.com/postman-docs/Screen Shot 2019-11-11 at 5.29.42 PM.png)

Specify a name, a summary, and select **Team** for type, then invite members to your newly created shared workspace.

## Team discovery

Enabling team discovery encourages collaboration and eases the onboarding process by allowing users accessing Postman with their company email address to request to join pre-existing teams within their organization.

### Making your team discoverable

You can enable team discovery in the web dashboard by selecting **Team** > **Settings**, or in the app by selecting **Team** > **Team Settings**.

[![team list](https://assets.postman.com/postman-docs/Screen_Shot_2019-11-11_at_5_18_37_PM.png)](https://assets.postman.com/postman-docs/Screen_Shot_2019-11-11_at_5_18_37_PM.png)

### Finding teams within your organization

When you log in to the Postman web dashboard using a verified email address for your company or organization, you can see available teams to join by selecting your avatar > **Your Team**.

You will see a list of available teams within your org. Select any team, then **Request to join**.

[![team list](https://assets.postman.com/postman-docs/Screen_Shot_2019-11-11_at_5_13_01_PM.png)](https://assets.postman.com/postman-docs/Screen_Shot_2019-11-11_at_5_13_01_PM.png)

The team administrator will receive a notification that you’ve asked to join the team. Once they approve your request, you will be able to access the team and collaborate on API projects within it.

## Usage limit for free users

Team workspaces are available to all users as of version 6.2. Postman usage limits differ by plan type and can be viewed on our [pricing page](https://www.getpostman.com/pricing).

### Usage limit

You can check the number of requests you've shared within the Postman app as well as in the web dashboard. Free users can select the drop-down menu to the right of **Upgrade** in the app. Paid users can access the menu by selecting your team name.

The usage menu allows you to review limits for shared requests and history, mocks, monitors, and public documentation. Click **Resource Usage** to view your usage period.

[![usage info](https://assets.postman.com/postman-docs/Screen Shot 2019-11-11 at 5.38.16 PM.png)](https://assets.postman.com/postman-docs/Screen Shot 2019-11-11 at 5.38.16 PM.png)

### How archiving works

 Postman archives collections when a free team's collaboration exceeds usage limits. Archived collections cannot be collaborated on, however they are still accessible to users. You will receive an in-app notification when a collection is archived.

[![archived message](https://assets.postman.com/postman-docs/Screen Shot 2019-11-11 at 5.44.36 PM.png)](https://assets.postman.com/postman-docs/Screen Shot 2019-11-11 at 5.44.36 PM.png)  

Postman chooses which collection(s) to archive based on last edit date. The collections that have gone the longest without a revision will be archived in order to bring your team within usage limits.

Postman indicates the number of archived collections at the bottom of the left sidebar.

[![archived message](https://assets.postman.com/postman-docs/ArchiveMsg2.png)](https://assets.postman.com/postman-docs/ArchiveMsg2.png)  

### Recovering your archived collections

To recover archived collections, select **Archived Collections**.

You will then be directed to your web dashboard, where you can click **Download your data** > **Request data export** > **Request an archive**.
[![export data1](https://assets.postman.com/postman-docs/Recovering_ArchivedCol1.png)](https://assets.postman.com/postman-docs/Recovering_ArchivedCol1.png)

You will then be able to select **Download** to retrieve your archived data.

[![Download Data](https://assets.postman.com/postman-docs/Download_Data1.png)](https://assets.postman.com/postman-docs/Download_Data1.png)

Alternatively, you can download your archived data directly within the Postman App. To learn how, refer to [Settings](/docs/postman/launching-postman/settings/).

## Next steps

For a more in-depth introduction to workspaces and how they can help organize your API development, check out [Intro to Workspaces](/docs/postman/workspaces/intro-to-workspaces/).
