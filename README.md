# Jenkins_Application

***About***

Steps to Set Up Jenkins Pipeline for Java Application

**1. Install Plugins:**

Git, Maven Integration, Pipeline, and Kubernetes Continuous Deploy plugins.

**2. Create Pipeline Job:**

Create a new pipeline job in Jenkins.

Configure it with the Git repository URL.

**3. Define Pipeline Stages:**

Checkout: Pull source code from Git.

Build: Use Maven to build the application.

Unit Tests: Run tests with JUnit and Mockito.

Code Quality: Perform SonarQube analysis.

Package: Create a JAR file.

Deploy to Test: Use Helm to deploy to a test environment.

User Acceptance Tests: Run tests on the deployed application.

Promote to Production: Deploy using Argo CD.

**4. Configure Stages:**

Use respective plugins for each stage (Git, Maven, JUnit, SonarQube, Kubernetes, and Argo CD).

**5. Set Up Argo CD:**

Install Argo CD on Kubernetes.

Track changes in Helm charts with a Git repository.

Create and add Helm chart to the repository.

**6. Integrate Jenkins with Argo CD:**

Add Argo CD API token to Jenkins credentials.

Update pipeline to include Argo CD deployment stage.

**7. Run Pipeline:**

Trigger the pipeline and monitor its progress. Fix any issues that arise.
