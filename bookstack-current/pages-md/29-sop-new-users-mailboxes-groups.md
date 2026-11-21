# SOP: New Users, Mailboxes & Groups

This SOP is written for SHHA staff who are comfortable with basic Microsoft admin work and need a reliable step-by-step process for setting up new groups, shared mailboxes, and related addresses.

**Any SHHA volunteer who wants their own SHHA email address may have one.** A personal address such as `first.last@sandiahomeowners.org` is available to volunteers as well as staff. Volunteers may also keep using personal email for committee messages and approved SharePoint guest access. Ask office staff for your preferred option; see [account setup and current license costs](https://wiki.sandiahomeowners.org/books/shha-it-help-guide/page/sop-new-users-mailboxes-groups).

**License cost:** SHHA currently pays about **$7 per month for each licensed account** (November 17, 2026). Set up accounts for actual requests; do not buy extra licenses in anticipation of future volunteers. Check whether a suitable paid license is already available before arranging another purchase.

For an email-address request, contact [office staff](mailto:office@sandiahomeowners.org). For setup or access problems, contact [IT Help](mailto:ithelp@sandiahomeowners.org).

**Start here every time:** [admin.microsoft.com](https://admin.microsoft.com)

---

## Quick Start: What Are You Trying to Set Up?

<table id="bkmrk-if-you-need...go-to-"><thead><tr><th>If you need...</th><th>Go to this section</th></tr></thead><tbody><tr><td>A new task-force or committee mailing address that sends to all members</td><td>[SOP A: Create a Microsoft 365 Group (Mailing List)](#bkmrk-sop-a%3A-create-a-micr)</td></tr><tr><td>A SharePoint document site for a new committee or task force</td><td>[SOP: Create a Committee SharePoint Site](https://wiki.sandiahomeowners.org/books/shha-it-help-guide/page/sop-create-a-committee-sharepoint-site)</td></tr><tr><td>A shared mailbox for one of the six officer roles</td><td>[SOP B: Create a Shared Mailbox](#bkmrk-sop-b%3A-create-a-shar)</td></tr><tr><td>A friendly one-off address like wildfire@sandiahomeowners.org</td><td>[SOP C: Add an Alias](#bkmrk-sop-c%3A-add-an-alias-)</td></tr><tr><td>A personal SHHA email account for a volunteer or staff member, such as first.last@sandiahomeowners.org</td><td>[SOP D: Add a Licensed User](#bkmrk-sop-d%3A-add-a-new-lic)</td></tr><tr><td>An external volunteer using Gmail/Yahoo/etc.</td><td>[SOP E: Add an External Guest](#bkmrk-sop-e%3A-add-an-extern)</td></tr></tbody></table>

---

## Task Force Fast Path (Most Common New Setup)

For a new short-term task force, the normal pattern is:

1. Create a **Microsoft 365 Group** for the task-force mailing list.
2. Add members (including external guests) and always include `admin@sandiahomeowners.org`.
3. If the request is for one of the six officer roles, use **SOP B** for the role mailbox. Ordinary committee chairs and task-force leads do not get shared mailboxes.
4. Add an optional **Alias** (for example, `wildfire@sandiahomeowners.org`) if a friendlier address is useful.
5. Confirm the Microsoft 365 group-connected **SharePoint site** exists; do not create a duplicate.
6. Configure document permissions using [SOP: Create a Committee SharePoint Site](https://wiki.sandiahomeowners.org/books/shha-it-help-guide/page/sop-create-a-committee-sharepoint-site) and send members the [Committee SharePoint Guide](https://wiki.sandiahomeowners.org/books/shha-it-help-guide/page/committee-sharepoint-guide).
7. Test email delivery, update the Quick Links directory, and send the [New Committee Or Task Force](https://wiki.sandiahomeowners.org/books/shha-it-help-guide/page/office-onboarding-email-templates) email if this is a new group.

If you only need one address that emails the whole task force, do **SOP A** only.

---

## SOP A: Create a Microsoft 365 Group (Mailing List)

**Use this for:** any committee/task-force address that should email all members.

**Menu path:** [admin.microsoft.com](https://admin.microsoft.com) → **Teams &amp; groups** → **Active teams &amp; groups** → **Add a group**

### Step-by-step

1. Open [admin.microsoft.com](https://admin.microsoft.com) and sign in.
2. In the left menu, click **Teams &amp; groups**.
3. Click **Active teams &amp; groups**.
4. Click **Add a group**.
5. Select **Microsoft 365** as the group type, then click **Next**.
6. Enter: 
    - **Name**: Full task-force name (example: Wildfire Preparedness Task Force)
    - **Description**: Short purpose statement
    
    Click **Next**.
7. Add at least one **Owner** (usually office staff), then click **Next**.
8. Set: 
    - **Group email address** (example: `wildfiretf` → `wildfiretf@sandiahomeowners.org`)
    - **Privacy**: usually **Private**
    - Leave "Create a team for this group" **off** unless Teams is explicitly needed
    
    Click **Next** then **Create group**.
9. After the group is created, open the new group and go to its **Settings** pane.
10. **Required:** check **Let people outside the organization email this team**.
11. **Required:** check **Send copies of team emails and events to team members' inboxes**.
12. Go to **Members** → **Add members**.
13. Add all task-force members (internal and external as available).
14. **Required:** Add `admin@sandiahomeowners.org` as a member for archive continuity.
15. Send a test email to the new group address and confirm delivery.
16. Send the [New Committee Or Task Force](https://wiki.sandiahomeowners.org/books/shha-it-help-guide/page/office-onboarding-email-templates) email after the group, membership, and any SharePoint site are tested.

**Test after every change:** whenever membership or a group setting changes, test the group again. You can add yourself temporarily, send a test message, and remove yourself afterward. If external delivery matters, you can also add a personal Gmail account temporarily, test it, and remove it when finished.

### Done checklist

- Group exists
- Owners added
- All members added
- External email enabled
- Inbox delivery enabled
- `admin@` added
- Test email delivered after setup and after any later change

---

## SOP B: Create a Shared Mailbox (Six Officer Roles Only)

**Use this only for:** President, Vice President, Secretary, Treasurer, ACC Chair, or CSC Chair. Shared mailboxes are a little fussy to administer, but officer history is important enough that SHHA keeps it this way.

**Do not use this for:** ordinary committee chairs, task-force leads, external volunteers, or general committee communication. Use the person's own account and the committee Microsoft Group instead.

**Menu path:** [admin.microsoft.com](https://admin.microsoft.com) → **Teams &amp; groups** → **Shared mailboxes** → **Add a shared mailbox**

### Step-by-step

1. Confirm the role is one of the six officer roles above. If it is any other chair or lead, stop and use the committee mailing-list procedure.
2. Click **Add a shared mailbox**.
3. Enter the role name and address, such as `president@sandiahomeowners.org`.
4. Save the mailbox, then open its details and choose **Members** → **Edit** → **Add members**.
5. Add the incoming officer's licensed `@sandiahomeowners.org` account.
6. Grant that account both **Full Access** and **Send As**. These are separate permissions; grant both.
7. Send the [Officer Shared Mailbox Access](https://wiki.sandiahomeowners.org/books/shha-it-help-guide/page/office-onboarding-email-templates) email with the direct role address and the wiki link.
8. Ask the officer to sign in to [Outlook](https://outlook.office.com) with their own account and manually add the shared mailbox. It will not appear automatically in every Outlook setup.
9. Test that the officer can open the mailbox, read an incoming test message, and send with the role address in the **From** field.
10. Tell the officer to send official role correspondence from the role mailbox or copy it. The shared mailbox is the role's archive; a personal inbox is not.

### Important notes

- The officer does **not** log in directly to the shared mailbox. There is no separate shared-mailbox password to give them.
- For current Outlook instructions, see [Open and use a shared mailbox in Outlook](https://support.microsoft.com/en-us/outlook/sharing/open-and-use-a-shared-mailbox-in-outlook).
- For a change of officer, remove the outgoing officer's permissions, grant the incoming officer both permissions, and test again.

---

## SOP C: Add an Alias (One-Off Friendly Address)

**Use this for:** addresses like `wildfire@sandiahomeowners.org` that should route to an existing group or mailbox.

**Menu path:** [admin.microsoft.com](https://admin.microsoft.com) → select target group/mailbox → **Email aliases** / **Email address** settings

### Step-by-step

1. Decide destination first: should alias route to the **group** or the **shared mailbox**?
2. For group destination: 
    - Go to **Teams &amp; groups** → **Active teams &amp; groups**.
    - Select the group.
    - Open email settings and add alias address.
3. For shared mailbox destination: 
    - Go to **Teams &amp; groups** → **Shared mailboxes**.
    - Select mailbox.
    - Open email settings and add alias address.
4. Save changes.
5. Send test email to alias and verify it arrives in the expected destination.

---

## SOP D: Add a licensed user for a volunteer or staff member

**Use this for:** any volunteer requesting an SHHA email address, and staff who need a personal SHHA account (`first.last@sandiahomeowners.org`).

**Menu path:** [admin.microsoft.com](https://admin.microsoft.com) → **Users** → **Active users** → **Add a user**

### Step-by-step

1. Confirm the person wants their own SHHA email address. Volunteers are eligible; being staff or an officer is not a requirement.
2. Check existing users for an account belonging to this person, then check whether a suitable paid license is already available. Ask the authorized license purchaser to arrange a license only if this request needs one. Do not purchase spare licenses.
3. Go to **Users → Active users → Add a user**. Enter the person's name and `first.last@sandiahomeowners.org` username.
4. Generate a temporary password and require a password change at first sign-in. Provide the temporary password through a separate approved channel from the username and welcome instructions.
5. Assign the appropriate license and finish creating the user. Ordinary email users do not need an administrator role.
6. Add the account to the approved committee groups. Grant shared-mailbox permissions only when the person holds one of the six designated officer roles.
7. Have the person sign in to Outlook, receive and send a test message, and open their committee Documents library. Verify the intended account is in use.
8. Send the licensed-user welcome message from the Office Onboarding Email Templates and link the Volunteer with SHHA Email guide.

---

## SOP E: Add an External Guest (Volunteer)

**For office staff and IT setting up a volunteer who will use personal email.** The Microsoft invitation lets the person sign in as an SHHA guest. The committee group gives that guest access to its documents and mailing list. Complete both steps.

Confirm the volunteer’s exact personal email address and approved committee. Use the [committee mailing address in Quick Links](/link/3) to identify the right group.

### 1. Invite the personal email address

1. Open the [Microsoft Entra admin center](https://entra.microsoft.com/) with an authorized SHHA account. Go to **Entra ID → Users → All users**. Search for the person first. If they already have an SHHA guest record for this email, reuse it and check the invitation status.
2. For a new guest, select **New user → Invite external user**.

[![New user menu with Invite external user](https://wiki.sandiahomeowners.org/uploads/images/gallery/2026-11/2U73BDRnIkk6pJpY-invite-menu.jpg)](https://wiki.sandiahomeowners.org/uploads/images/gallery/2026-11/2U73BDRnIkk6pJpY-invite-menu.jpg)

*Choose Invite external user to send an invitation to the volunteer’s personal email.*

3. On **Basics**, enter the personal email address and the name the office will recognize. Keep **Send invite message** selected. In **Message**, identify SHHA and include the Welcome page address. Use the example below.
4. Select **Review + invite**. Check the email spelling and confirm **User type** is **Guest**, then select **Invite**. Microsoft sends the invitation to that inbox.

[![Invite external user form filled with a fictional name and personal email](https://wiki.sandiahomeowners.org/uploads/images/gallery/2026-11/08sVx0rhLKGMkTqx-invite-basics.jpg)](https://wiki.sandiahomeowners.org/uploads/images/gallery/2026-11/08sVx0rhLKGMkTqx-invite-basics.jpg)

*Enter the personal email and display name. The example address is for illustration. Keep Send invite message selected and include the welcome page in Message.*

> Welcome to SHHA! Choose Accept invitation and sign in using this email address. First steps: https://wiki.sandiahomeowners.org/books/shha-it-help-guide/page/welcome-to-shha

### 2. Confirm the invitation was accepted

Ask the volunteer to follow [Welcome to SHHA](https://wiki.sandiahomeowners.org/link/49). In **Entra ID → Users**, open their guest record and check the invitation status. If it still shows pending, confirm the address and ask them to check Spam or Junk. Use the guest record’s **Resend invitation** action if needed.

### 3. Add the guest to the approved committee group

1. Go to **Entra ID → Groups → All groups**. Search for the committee by name. Verify the group type is **Microsoft 365** and match its email to the mailing address in [Quick Links](/link/3). For example, the Environment &amp; Safety Committee uses **ESC@sandiahomeowners.org**. Select the committee group for ordinary committee access.

[![Group search showing the Environment and Safety Committee and its Chair group](https://wiki.sandiahomeowners.org/uploads/images/gallery/2026-11/U8pnUqQn6mmU9Tap-committee-group-search.jpg)](https://wiki.sandiahomeowners.org/uploads/images/gallery/2026-11/U8pnUqQn6mmU9Tap-committee-group-search.jpg)

*Check the full name and address. The first result is the committee group in this example.*

2. In the selected group, open **Members**, then **Add members**.

[![Committee Members page with Add members and Direct members controls](https://wiki.sandiahomeowners.org/uploads/images/gallery/2026-11/QKWC3CN3n5lnMjNQ-committee-members.jpg)](https://wiki.sandiahomeowners.org/uploads/images/gallery/2026-11/QKWC3CN3n5lnMjNQ-committee-members.jpg)

*Open the selected committee’s Members page. Choose Add members.*

3. Search by the guest’s display name. Match the result to the guest record for the invited email, especially if two people have similar names. Select the guest, then choose **Select** at the bottom to add them as a group member.
4. Return to **Direct members** and check that the guest appears in the list.

[![Add members picker with a name search, Selected count and Select button](https://wiki.sandiahomeowners.org/uploads/images/gallery/2026-11/hdqLandb3fKs7Kfp-committee-add-members.jpg)](https://wiki.sandiahomeowners.org/uploads/images/gallery/2026-11/hdqLandb3fKs7Kfp-committee-add-members.jpg)

*Search for the volunteer, choose the matching guest and select Select. The fictional name in this picture has no result.*

### 4. Check the volunteer’s access

1. Send the committee site address and the [Welcome to SHHA](https://wiki.sandiahomeowners.org/link/49) page. Ask the volunteer to sign in with the invited address and open **Documents**.
2. Confirm the volunteer can open the intended library and receives a test message sent to the committee list. If either fails, check the accepted invitation and the group membership for the same email. Use [the external volunteer email template](/link/15) for your handoff.

For provider details, see [Microsoft’s guest invitation instructions](https://learn.microsoft.com/en-us/entra/fundamentals/how-to-create-delete-users#invite-an-external-user) and [group membership instructions](https://learn.microsoft.com/en-us/entra/fundamentals/how-to-manage-groups#add-members-or-owners-of-a-group).

---

## Send The Onboarding Email

After setup and testing are complete, choose the matching message from [Office Onboarding Email Templates](https://wiki.sandiahomeowners.org/books/shha-it-help-guide/page/office-onboarding-email-templates). Replace every placeholder and test every link before sending.

## Final Validation (Do This Before You Tell the Office Contact Setup Is Complete)

- Group email tested
- Shared mailbox tested (if created)
- Alias tested (if created)
- `admin@` included in group
- Quick Links directory updated with new addresses
- Office contact told setup is complete

---

## Reset a forgotten Microsoft 365 password

These steps are for an authorized Microsoft administrator handling a request for an SHHA-managed work account. Verify the request and the user’s identity through a known contact method before resetting anything. Confirm the account in Microsoft. A personal Microsoft account or an account managed by a guest’s home organization must be recovered through that provider or organization. For a guest who signs in with an email code, help them use the invited address and request a fresh code. If you do not have the required Microsoft role, forward the request to [IT Help](mailto:ithelp@sandiahomeowners.org).

1. Open the [Microsoft 365 admin center](https://admin.cloud.microsoft/) and go to **Users → Active users**.
2. Select the verified SHHA account, choose **Reset password**, and generate a temporary password. Keep the option to require a new password at the next sign-in selected if it is shown. Select **Reset password** to finish.
3. Send the sign-in instructions to the requester’s verified alternate contact. Give them the temporary password through a separate approved channel. If using an approved encrypted message for the password, replace `[TEMPORARY PASSWORD]` in that message only. Keep the password out of ordinary email, the wiki, and Ask the Wiki.

### Copy after completing the reset

**Subject:** Your SHHA Microsoft password was reset

Hi \[FIRST NAME\],

I reset the password for your SHHA Microsoft account (\[SHHA SIGN-IN EMAIL\]). I’ll share your temporary password separately via \[APPROVED CHANNEL\]. Go to https://www.microsoft365.com/ and sign in with your SHHA email and the temporary password. Microsoft will prompt you to choose a new password.

If you still can’t sign in, reply with the error message. Please leave out passwords and verification codes.

Thanks,  
\[YOUR NAME\]

**Separate secure message:** Your temporary Microsoft password is \[TEMPORARY PASSWORD\]. Microsoft will ask you to choose a new password when you sign in.

See Microsoft’s [password reset instructions](https://learn.microsoft.com/en-us/microsoft-365/admin/add-users/reset-passwords) and [account ownership and administrator role requirements](https://learn.microsoft.com/en-us/entra/fundamentals/users-reset-password-azure-portal).

## Where To Go Next

- [M365 Email Building Blocks](https://wiki.sandiahomeowners.org/books/shha-it-help-guide/page/m365-email-building-blocks) for choosing the right pattern first
- [M365 Email Groups, Role Inboxes &amp; Responsibilities](https://wiki.sandiahomeowners.org/books/shha-it-help-guide/page/m365-email-groups-role-inboxes-responsibilities) for governance and handoff rules
- [SOP: Create a Committee SharePoint Site](https://wiki.sandiahomeowners.org/books/shha-it-help-guide/page/sop-create-a-committee-sharepoint-site) for document-library setup and permissions
- [Quick Links &amp; Directory](https://wiki.sandiahomeowners.org/books/shha-it-help-guide/page/quick-links-directory) to keep the address list current
