# inception-pipe

The inception pipe manages the product & design work that happens prior to an issue enters the delivery pipe. Its goal is to streamline the processes that currently happen across different tools and increase the transparency and visibility of this work to the community.

It shall allow everyone to follow (and comment) the progress of issues while being in inception without the need to keep up with slack conversations across multiple channels.

**V1:** The Inception Pipe covers the inception process from **AFTER** issues have been prioritized in product curation. 

**V2:** In the long run, the inception pipe is going to include the **entire process from "Discovery Phase 1" until ready for the delivery pipe**, i.e. is going to be a place where all issues with "Potential for Inception" - design projects, wishlist items etc. - will be collected, categorised and prioritised

About this pipe are here:
https://www.notion.so/openfoodnetwork/Inception-Pipe-cc778fa5364a4f6f8e2dd81f8e33d19a


# Inception Pipe

### 1. Process: Inception Pipe → Delivery Pipe

The **Inception Pipe** is connected with the Delivery Pipe so that issues that are ready incepted move automatically into the Delivery Pipe and allow the entire product development process to be synced and managed in one common place.

**ZenHub Workflows** allows teams to sync the pipeline state of an Issue in multiple Workspaces. By setting up a Workflow, you can automate the movement of Issues between different Workspaces. This ensures Boards are always up to date reflecting the most current picture of progress in every teams Workspace.

![Zenhub workflows-examples.png](/workflows-examples.png)

### 2. The Pipe: Columns & Labels

**COLUMNS**

- **Ready for Inception**

    Upcoming Issues that have been prioritised from product curation. They can come from wishlist, papercuts, user research, instances, grant funding etc.

- **In Inception**

    Issues for which the inception process has been kicked-off. Additional clarification / research is still needed. Discussions with Tech and Design happen here already if needed.

- **Ready for Design**

    Where design input is needed post product inception. Issues have most information required for design work to be kicked off.

- **In Design**

    This is actively being designed and has all or most design requirements. A designer is assigned. This can mean UX research, design thinking or 'visual' design.

- **Review**

    Issues open to the team for review. If approved, Issue goes into the Dev Pipe, otherwise back to "In Inception" or "In Design"

- **Done** / **Ready for Dev**

    Issues that are reviewed and approved. They go at the same time into the Dev Pipe ("Dev Ready") → **using the Zen Hub Feature to connect workspaces**

    **LABELS**
 
 Issues that cannot move forward in the pipe, until they get input from Design, Tech or Product

- Blocked: Design Input needed
- Blocked: Tech Input needed
- Blocked: Product Input Needed

Labels about where the issue/epic is coming from

- Wishlist
- Papercut
- Feature request
- etc.
