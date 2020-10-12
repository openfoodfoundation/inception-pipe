# inception-pipe

About this pipe are here:
https://www.notion.so/openfoodnetwork/Inception-Pipe-cc778fa5364a4f6f8e2dd81f8e33d19a


# Inception Pipe

### 1. Process: Inception Pipe → Delivery Pipe

The **Inception Pipe** is connected with the Delivery Pipe so that issues that are ready incepted move automatically into the Delivery Pipe and allow the entire product development process to be synced and managed in one common place.

**ZenHub Workflows** allows teams to sync the pipeline state of an Issue in multiple Workspaces. By setting up a Workflow, you can automate the movement of Issues between different Workspaces. This ensures Boards are always up to date reflecting the most current picture of progress in every teams Workspace.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a9764ae6-e946-447c-8720-70341843c6ba/workflows-examples.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a9764ae6-e946-447c-8720-70341843c6ba/workflows-examples.png)

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

- Blocked: Design Input needed
- Blocked: Tech Input needed
- Blocked: Product Input Needed

Labels about where the issue/epic is coming from

- Wishlist
- Papercut
- Feature request
- etc.
