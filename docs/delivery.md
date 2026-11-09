# Delivery

Default stop: **development**. Ordered stops: **development → main**.

## development

Operator: agent.

Run [verification](../README.md#verification), review and commit the task's source, integrate it into development and push. Verify that the live origin/development contains the task commit.

## main

Operator: agent.

Follow [publishing](../README.md#publishing): merge checked development into main and let the existing Pages workflow verify and deploy its static artifact. Confirm the successful deployment's source revision and compare the live site with that checked artifact.

## Evidence and cleanup

Report live branch/HEAD, committed source, remote containment and the reached stop; main additionally needs its deployed source revision. Remove only this task's clean, integrated, inactive worktree, local/remote task branches and temporary folders. Name anything retained and why.
