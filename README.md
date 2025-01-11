# DVC-Hands-On-Practice

This is just a repository which has helped me gain hands on experience on DVC. I have used S3 folder for local storage and by tracking this folder with DVC I was able to rollback to my previous versions.

# Prerequiste
Must have an idea on how to manipluate the repository using git commands.

# Instructions
1 - First install dvc with pip install dvc.

2 - Then dvc init (This will result in error for this case because git is tracking data so running this command will suggest two commands which you must run before dvc init)

3 - Now since we are using dvc and github, they must go hand in hand so like github you must first use dvc commit and dvc push to push the data to storage after this push code changes on github

4 - Once you rollback to previous commint, dvc pull so that you have the corresponding data of that version.


