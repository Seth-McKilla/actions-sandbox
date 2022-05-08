# GitHub Actions Sandbox

An ever-expanding collection of GitHub actions striving to automate as many things as possible 🤖

## Directory

<hr>

## [Workflow Dispatch](./.github/workflows/workflow-dispatch.yml)

Manually trigger an action through a GitHub REST API request. This action should be dispatched when a POST request is sent to: https://api.github.com/repos/{user_name}/{repo_name}/actions/workflows/{action_filename}.yml/dispatches

<br>

(For this repo, https://api.github.com/repos/Seth-McKilla/actions-sandbox/actions/workflows/workflow-dispatch.yml/dispatches was used)

<br>

**Note: A [personal access token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token) with the "workflow" scope selected and [basic authentication](https://docs.github.com/en/rest/overview/other-authentication-methods#via-oauth-and-personal-access-tokens) is needed to trigger the action and successfully receive 204 response code**

<br>

### 🌐 Checkout this [public Postman workspace](https://www.postman.com/sethmckilla/workspace/github-actions-sandbox/collection/11010551-04ad5305-b19b-4e45-b50e-3f2fecfe5b26?ctx=documentation) to easily setup your API testing environment. Simply navigate to the workspace and follow these three steps to get up and running in no time!

1. Navigate to the [workspace](https://www.postman.com/sethmckilla/workspace/github-actions-sandbox/collection/11010551-04ad5305-b19b-4e45-b50e-3f2fecfe5b26?ctx=documentation) and fork it
2. Set your GitHub username and personal access token in the "Variables" tab of the collection
3. Fire off the request (make sure you've cloned this repo first!) to watch your action get triggered 🚀

<br>

Resources
<br>
[workflow_dispatch documentation](https://docs.github.com/en/actions/using-workflows/events-that-trigger-workflows#workflow_dispatch)
<br>
[Getting started with the GitHub REST API](https://docs.github.com/en/rest/guides/getting-started-with-the-rest-api)

<hr>
