# action-repo

This repository is created as part of the TechStaX developer assessment.

The purpose of this repository is to act as a source for GitHub events such as **Push**, **Pull Request**, and **Merge** actions. These events are captured using GitHub Webhooks and sent to a registered webhook endpoint implemented in the `webhook-repo`.

This repository does not contain any application logic. It is used solely to trigger GitHub events by performing commits, creating pull requests, and merging branches, which are then processed, stored, and displayed by the webhook receiver and UI.

## Events Triggered

- Push
- Pull Request
- Merge

## Usage

- Make commits to trigger **Push** events.
- Create pull requests to trigger **Pull Request** events.
- Merge pull requests.

All webhook payloads from this repository are sent to the webhook endpoint configured in the GitHub Webhooks settings.
