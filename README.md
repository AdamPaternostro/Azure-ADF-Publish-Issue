# Azure-ADF-Publish-Issue
Used to demonstrate how ADF overwrite the adb_publish files upon branching

ADF does not allow you to publish a branch by pressing the Publish button.

You have to merge back to main/master and then press publish which will overwrite the files in the adf_publish branch.  This makes having many feature branches and hotfixes very hard to manage.

To see my preferred method: https://github.com/AdamPaternostro/Azure-Data-Factory-CI-CD-Source-Control
