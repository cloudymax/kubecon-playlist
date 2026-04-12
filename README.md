## Gaming
- [What Survived Production: Operating Game Backends at Million-Player Scale - Berkay Uckac](https://www.youtube.com/watch?v=Aa04SuPhxtA)
- [From Creepers to Clusters: Evolving Minecraft Into a Cloud Native... Jaden Walderich & Alex Mizerak](https://www.youtube.com/watch?v=XAJySxpKdzo)
- [Keynote: How Ubisoft Orchestrates Global Multiplayer Games wit... Jean-François Hubert & Mark Mandel](https://www.youtube.com/watch?v=MUOd6IoLC5Q)
  - Use CNCF tooling because AWS/GCP/Azure too dificult to keep up with compatibility.
  - Write once deploy anywhere
- [From Projects to Products: The Sociotechnical Journey Behind Sony... Eugenia Bergman & Hagen Tonnies](https://www.youtube.com/watch?v=zrXvt9DXQ3U)

## Observability
- [Smoothed and Anchored Rate Calculation in PromQL - Björn Rabenstein, Grafana Labs](https://www.youtube.com/watch?v=iN5vQjDuiWc)

## Platform Engineering
- [Crossplane - The Cloud Native Framework for Platform Engineering - Jared Watts & Adam Wolfe Gordon](https://www.youtube.com/watch?v=zu6V34BFksk)
- [Policy Engines for Kubernetes: Picking One Without Losing Your Mind - Nabarun Pal, Broadcom](https://www.youtube.com/watch?v=y5rrfSZBm1A)
- [Flipping the Curve: A Platform Engineer's Guide to Unlocking the Silent 80% - Michael Reichenbach](https://www.youtube.com/watch?v=xRpGhFihQpk)
- [Amplifying End User Voices: Platform Architects on the... Rajas K, Zach S, Kevin K, Elias T & Dawn C](https://www.youtube.com/watch?v=7uBB4qgh2R0)
- [How to Build a European Cloud Orchestration Platform From With... Maximilian Techritz & Johannes Ott ](https://www.youtube.com/watch?v=hR8hFht9sFA)
- [Keynote: Building a Sovereign, Multi-Cloud Strategy with Cloud Native Technolog... Goetz Reinhaeckel](https://www.youtube.com/watch?v=ic814zjd454)
- [Panel: Building a GitOps... Dan Garfield, Revital Barletz, Antonela Cukurin, & Gabriel Quennesson](https://www.youtube.com/watch?v=EYk72vXAJrU)
- [Cloud Native Theater | Cloud Native University: Platform Engineering - About Tools... Max Körbächer](https://www.youtube.com/watch?v=jhF3sTA7B0M)

## Kubevirt
- [API is the New SSH: Forging a Zero-Trust VM Platform on Kubernetes - Evangelista Tragni, Devoteam ](https://www.youtube.com/watch?v=mVcBnbSfBrs)
- [KubeVirt's Evolution: Governance, Features, and Community Growth - Sreeja Varnam & Luboslav Pivarc](https://www.youtube.com/watch?v=goCjV2xJDnk)
- [Cloud Native Theater | KubeVirt Summit: Bridging Islands: EVPN Overlays for Multi-C... Miguel Duarte](https://www.youtube.com/watch?v=P0V_IiI3Qh4)
- [In-place Updates with Cluster API: The Sweet Spot Between Immu... Fabrizio Pandini & Stefan Büringer](https://www.youtube.com/watch?v=CMf6rOPo9Z0)

## Argo
- [Project Lightning Talk: Argo Workflows 4, What's New And What's Next - Alan Clucas, Lead](https://www.youtube.com/watch?v=YbW24qbJ78I)
  - reusable containers
  - expressions overhaul
  - bring your own artifact driver
- [Bring Your Own Artifact Driver To Workflows - Alan Clucas, Pipekit](https://www.youtube.com/watch?v=kF6zuGZAgI0)
- [Don't Do What Donny Don't Does: The 10 Dos and 500 Don’ts of Workflows... Tim Collins & Becky Pauley](https://www.youtube.com/watch?v=tzCGRezWJzQ)
  - its kubernetes
  - configure time to check in on workflow steps
  - only run 1 workflow controller replica
  - archive old workflows
  - use java/python/go SDKs if you dont like yaml
- [Project Lightning Talk: Argo CD Source Hydrator: Rendered Manifests Made Easy! - Michael Crenshaw](https://www.youtube.com/watch?v=Lkik-mrYfP4)
  - seems pretty easy to set up.
- [Argo CD: Previewing Pull Request Changes in SECONDS! - Dag Bjerre Andersen & Sergey Shevchenko](https://www.youtube.com/watch?v=fcajag5di68)
- [Cross-Cluster Progressive Delivery: Rolling Out Apps With Arg... Carlos Santana & Elamaran Shanmugam](https://www.youtube.com/watch?v=_2vRm81KyIk)

## Istio
- [From NLB Sprawl To Mesh Efficiency: How Skyscanner Handles 60M Reque... John Clark & Steven Thwaites](https://www.youtube.com/watch?v=2ZvvGdHfknM)
- [Cloud Native Theater | Istio Day: Panel: Horrors and Successes of Running Istio in Production](https://www.youtube.com/watch?v=-Z9zvo6leRY)
  - upgrades are hard
  - multi-cluster mesh seems pretty popular

## Other
- [Helm 4 Is Here. So, Now What? - Andrew Block, Red Hat; Scott Rigby, Replicated; Robert Sirchia, SUSE](https://www.youtube.com/watch?v=cmHFJikhmyY)
  - Soon:
    - new template languages (CUE)
    - helmignore work like gitignore
    - better handling of subchart values
    - better oci and auth support
- [Virtual Power Plants (VPP): How They Work and What They Are - LeRenzo Malcom & Mario Flores, Enpal](https://www.youtube.com/watch?v=95cFjYJS4ek)
  - VPPs are frickin cool
- [Rook: Intro and Deep Dive With Ceph Storage - Artem Torubarov, Deepika Upadhyay & Niels de Vos](https://www.youtube.com/watch?v=ygE67l9b2Mc)
- [Evolving Baremetal-as-a-Service: Secure Multi-Cluster Network... Yushiro Furukawa & Mitsuhiro Tanino](https://www.youtube.com/watch?v=MgerB2Tl0MQ)
- [GPUs on Kubernetes: What Actually Happens When You Request Nvidia... Gulcan Topcu & Daniele Polencic](https://www.youtube.com/watch?v=nu6bLhuvlWM)
- [Project Lightning Talk: CNCF Sandbox Project K8Up Under The Hood - Aarno Aukia, Maintainer](https://www.youtube.com/watch?v=NtXvB9gWTu8)
  - add self to adopters
- [Project Lightning Talk: K3s Lightning Update - Manuel Buil, Maintainer](https://www.youtube.com/watch?v=ouMh2xk0XFI)
  - add self to adopters
- [Scaling Valkey the Right Way: Kubernetes at XL Scale - Sarthak Aggarwal & Madelyn Olson, AWS](https://www.youtube.com/watch?v=t0qax1qQm14)
  - Valkey working on their own cluster operator
  - use the Valkey glide client
