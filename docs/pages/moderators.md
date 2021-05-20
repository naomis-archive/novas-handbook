# Moderator Guidelines

This page is for our current moderators. It is intended to serve as a reference for handling moderation issues within our community.

Being a moderator does not mean that you are above our community, and we ask that you do not behave as such. It simply means that you are trusted with additional tools to help ensure our community is safe.

## General Expectations

Our moderators are meant to be the example of ideal community members. As such, you should be active within our community, adherent to our rules, and welcoming to our members.

However, you are also still a member of the community yourself. Not every interaction needs to be a moderation action. Socialise with your fellow community members and remember that we are here to have fun!

We have many community platforms, some of which you may not be familiar with. That's okay! While you are trusted to maintain all of our platforms, you only need to moderate the ones you're comfortable with. If you have any questions, you can always reach out to your fellow moderators.

## GitHub

Moderating GitHub involves triaging issues and reviewing pull requests, as well as fostering communication between our contributors and enforcing our community guidelines.

### Triaging Issues

By default, when an issue is opened `nhcarrigan` is assigned and the issue gets a `🚦 status: awaiting triage` label automatically. This label is used to indicate issues that have not yet received attention from our maintainers.

The first step is to respond to the issue with a comment thanking the contributor for bringing it to our attention. If additional information is needed, ask the necessary questions to help identify the potential resolution for the issue.

Once a resolution has been reached, the issue will need to be re-labeled. Remove `nhcarrigan`'s assignment and the `🚦 status: awaiting triage` label. Then, apply the appropriate labels from the list. Each label has a description to help identify its purpose.

Be sure to include at least one label from the `aspect`, `goal`, `priority`, and `status` categories. Typically, the `status` label should be `🏁 status: ready for dev`.

If you aren't sure what labels to apply, use the `🏷 status: label work required` and leave everything else unlabelled, and another mod will come by to label it.

### Reviewing Pull Requests

Reviewing a pull request does require some understanding of the code base for that particular project. However, we are a community of learning, so if you would like some assistance reviewing a PR let another mod know! Someone will help you understand the changes.

The first step is to review the changes made to the code or files using GitHub's UI. You should make sure the changes are logical, add value, and do not add any spam or malicious content.

Then, using whichever method you prefer, pull the changes down locally (or use an environment like GitPod) and test the changes. Make sure the changes resolve the linked issue or implement the feature/fix as expected.

If you are happy with the changes made in the PR, add your review comments and select "Approve". If you would like to see changes, use the GitHub Suggestion feature where possible to create committable changes for the contributor to apply. When not possible, be as clear and descriptive as possible to make the process smoother for the contributor.

If you have any questions about this process, ask your fellow moderators.

## Discord

Moderating Discord primarily involves ensuring our members are interacting with each other in accordance with our rules. If a member is not acting appropriately, you should take action relative to their infraction.

### Warning a Member

For actions that are mostly harmless, such as mild spam, or an insult that isn't discriminatory (i.e. "You're a jerk"), you can issue a warning. Use Becca to give a warning to the member so the action is appropriately logged.

```txt
becca!warn @user this is the reason
```

### Kicking a Member

If a member is arguing with you directly, spamming a channel, or breaking our rules in a non-excessive manner, often times a kick is sufficient to show them that you are serious about enforcing our standards. Use Becca to kick the member so the action is logged.

```txt
becca!kick @user this is the reason
```

### Banning a Member

Careful consideration must happen before banning a member. Discord bans are IP specific and the member will not be able to rejoin until the ban is lifted. When you need to ban someone, use Becca to do so.

```txt
becca!ban @user this is the reason
```

Becca will ask you to confirm that you intend to do this.

## Working With Fellow Mods

On GitHub our community organisation has a `moderators` team. Within this team you can create private discussions that only your fellow moderators will see. On Discord, we have a private staff-chat channel for the same purpose.

These are places where you can bring up concerns, ask fellow moderators how they would approach a situation, or request assistance in dealing with an issue. We will gladly help you resolve the problems at hand.

Remember that we are a team. We do not want to disagree with each other publicly. If you have concerns about a moderation action, or about a fellow moderator's actions, discuss it in one of these private areas. If you cannot reach a resolution, reach out to nhcarrigan or DennaGrey for guidance.

## Activity Requirements

We do not require specific levels of activity from our moderators. We understand that you are volunteering your time to help our community, and it is highly appreciated.

That being said, if you anticipate being inactive for more than a week, we do ask that you let us know in the Discord staff-chat so we are aware that you will not be around to address issues.

## Becoming a Moderator

Moderators are selected based on activity and value in the community. We do not have an application or election process. Instead, our existing moderators will notice folks who are active and helpful and recommend them for promotion.

If you are selected to be a moderator, you will start on a trial basis with limited permissions - after a month, you will receive a performance review. At that time, we will either promote you to full moderator or provide feedback for you to strengthen your skills (and try again the next month).
