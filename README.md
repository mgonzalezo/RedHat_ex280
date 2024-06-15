# RedHat_ex280
Red Hat Certified OpenShift Administrator exam (EX280) Overview and Preparation


### Red Hat OpenShift Editions Summary

#### Red Hat OpenShift Local
- Deploys a cluster on a local computer for testing and exploration.
- Suitable for initial exploration of OpenShift.
- Not intended for production environments.

<canvas id="canvasLocal" width="300" height="150"></canvas>

<script>
var canvas = document.getElementById('canvasLocal');
var ctx = canvas.getContext('2d');
ctx.fillStyle = '#FF0000';
ctx.fillRect(10, 10, 280, 130);
ctx.fillStyle = '#FFFFFF';
ctx.font = '20px Arial';
ctx.fillText('Red Hat OpenShift Local', 20, 80);
</script>

#### Red Hat Developer Sandbox
- Provides 30 days of free access to a shared OpenShift cluster.
- Allows testing and exploration of OpenShift features.
- Not intended for production use.

<canvas id="canvasSandbox" width="300" height="150"></canvas>

<script>
var canvas = document.getElementById('canvasSandbox');
var ctx = canvas.getContext('2d');
ctx.fillStyle = '#00FF00';
ctx.fillRect(10, 10, 280, 130);
ctx.fillStyle = '#FFFFFF';
ctx.font = '20px Arial';
ctx.fillText('Red Hat Developer Sandbox', 20, 80);
</script>

#### Public Cloud Managed Services
- Quick access to OpenShift clusters on Amazon Web Services, Microsoft Azure, IBM Cloud, and Google Cloud.
- Managed by Red Hat and cloud providers, integrating with cloud infrastructure.
- Ideal for businesses seeking reliable and managed cluster deployments.

<canvas id="canvasManaged" width="300" height="150"></canvas>

<script>
var canvas = document.getElementById('canvasManaged');
var ctx = canvas.getContext('2d');
ctx.fillStyle = '#0000FF';
ctx.fillRect(10, 10, 280, 130);
ctx.fillStyle = '#FFFFFF';
ctx.font = '20px Arial';
ctx.fillText('Public Cloud Managed Services', 20, 80);
</script>

#### Self-Managed Editions
- Deployable on physical or virtual infrastructure, on-premise or in a public cloud.
- Offers greater control and flexibility but requires more management responsibility.
- Suitable for organizations that prefer to manage their own infrastructure and cluster services.

<canvas id="canvasSelfManaged" width="300" height="150"></canvas>

<script>
var canvas = document.getElementById('canvasSelfManaged');
var ctx = canvas.getContext('2d');
ctx.fillStyle = '#FFA500';
ctx.fillRect(10, 10, 280, 130);
ctx.fillStyle = '#FFFFFF';
ctx.font = '20px Arial';
ctx.fillText('Self-Managed Editions', 20, 80);
</script>

#### Red Hat OpenShift Kubernetes Engine
- Includes the latest Kubernetes platform with enhanced security and enterprise stability.
- Runs on Red Hat Enterprise Linux CoreOS and includes Red Hat OpenShift Virtualization.
- Provides an administrator console for operational support.

<canvas id="canvasKubernetesEngine" width="300" height="150"></canvas>

<script>
var canvas = document.getElementById('canvasKubernetesEngine');
var ctx = canvas.getContext('2d');
ctx.fillStyle = '#800080';
ctx.fillRect(10, 10, 280, 130);
ctx.fillStyle = '#FFFFFF';
ctx.font = '20px Arial';
ctx.fillText('OpenShift Kubernetes Engine', 20, 80);
</script>

#### Red Hat OpenShift Container Platform
- Builds on the OpenShift Kubernetes Engine with additional manageability, security, and development features.
- Includes a developer console, log management, cost management, and metering information.
- Adds Red Hat OpenShift Serverless (Knative), Service Mesh (Istio), Pipelines (Tekton), and GitOps (Argo CD).

<canvas id="canvasContainerPlatform" width="300" height="150"></canvas>

<script>
var canvas = document.getElementById('canvasContainerPlatform');
var ctx = canvas.getContext('2d');
ctx.fillStyle = '#FFD700';
ctx.fillRect(10, 10, 280, 130);
ctx.fillStyle = '#000000';
ctx.font = '20px Arial';
ctx.fillText('OpenShift Container Platform', 20, 80);
</script>

#### Red Hat OpenShift Platform Plus
- The most feature-rich edition, including all features of the Container Platform.
- Adds Red Hat Advanced Cluster Management, Advanced Cluster Security, and Red Hat Quay private registry.
- Designed for comprehensive development and administrative needs for containerized application management.

<canvas id="canvasPlatformPlus" width="300" height="150"></canvas>

<script>
var canvas = document.getElementById('canvasPlatformPlus');
var ctx = canvas.getContext('2d');
ctx.fillStyle = '#00CED1';
ctx.fillRect(10, 10, 280, 130);
ctx.fillStyle = '#000000';
ctx.font = '20px Arial';
ctx.fillText('OpenShift Platform Plus', 20, 80);
</script>

#### Red Hat Insights Advisor
- Available through the Red Hat Hybrid Cloud Console.
- Helps administrators identify and remediate cluster issues using data from the Insights Operator.
- Provides recommendations and their impacts on the cluster for proactive management.

<canvas id="canvasInsights" width="300" height="150"></canvas>

<script>
var canvas = document.g
