# Merge multiple commits into single commit

# Follow the steps below
    1. Run `git rebase -i HEAD~n`   (where n is number of commits)
        i) It will open an editor with list of commit and options to pick/  squash and many more
        ii) Replace pick with squash for the commits you want to combine into
        iii) Then press ESCAPE button and type :wq and press ENTER to save and exit
        iv) It will open again a new editor with front commit, you can edit it by press i(INSERT) and then update the final commit and again follow step iii.
    2) Now Run `git push -f origin <branch_name>

# You are done!, Happy moment, Enjoy!