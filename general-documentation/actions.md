# Actions

The actions system contains the following block types:

<details>

<summary><strong>DM User</strong></summary>

Send a Direct message to the user who sent the submission.

{% hint style="info" %}
Includes a character limit of 500 characters. You can add multiple blocks.
{% endhint %}

</details>

<details>

<summary><strong>Grant Roles</strong></summary>

Grant any selected roles from within the same server that the form was submitted in.

</details>

<details>

<summary><strong>Revoke/Remove Roles</strong></summary>

Take away any selected roles from within the same server which the form was submitted in.

</details>

<details>

<summary><strong>Delete Submission</strong></summary>

Delete the submission

</details>

{% hint style="danger" %}
The bot executes the actions **in the order they are placed**. If the submission is deleted in the first block, then the following actions cannot be completed.
{% endhint %}

There is a limit of **4 buttons**, and **10 actions per block**.
