# GitHub Actions Sandbox

A collection of GitHub action files for testing purposes and future reference.

## Directory

<hr />

## [Workflow Dispatch](./.github/workflows/workflow-dispatch.yml)

Manually trigger an action through a GitHub REST API request. This action should be dispatched when a POST request is sent to https://api.github.com/repos/{user_name | org_name}/{repo_name}/actions/workflows/{action_filename}.yml/dispatches
<br />
(For this repo, https://api.github.com/repos/Seth-McKilla/actions-sandbox/actions/workflows/workflow-dispatch.yml/dispatches was used)

**Note: A [personal access token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token) and [basic authentication](https://docs.github.com/en/rest/overview/other-authentication-methods#via-oauth-and-personal-access-tokens) is needed to trigger the action and receive a successful 204 response code**

<hr />
