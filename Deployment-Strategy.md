####
What are Git Tags, and How Do They Differ from Branches?

Git tags mark specific points in a repository's history, usually for releases. Tags are immutable, meaning they don't change once set. Branches, on the other hand, are used for ongoing development and can change as new commits are added.


####
How Can Git Tags Help in Managing and Tracking Deployments?

Git tags help manage deployments by marking exact commit points for releases, ensuring consistency and traceability. They can trigger automated CI/CD pipelines for reliable deployments.


####
How Would You Use Git Tags to Ensure a Stable and Reliable Deployment to the Client's Production Environment?

1.Create an annotated tag for the release (e.g., v1.0.0).
2.Push the tag to the remote repository.
3.Set up CI/CD to deploy when a new tag is pushed.
4.Use post-deployment checks and have a rollback plan.


####
What Steps Should Your Team Take to Ensure That the Client's Production Environment Remains Unaffected by Ongoing Development?

1.Use separate branches for development.
2.Implement feature flags.
3.Use a staging environment for testing.
4.Conduct thorough code reviews.
5.Deploy changes in phases and monitor for issues.
