# Github Machine Learning Playground Data Info

### Stephen Kirby


## Source: GithubTorrent Project

This project was made possible by the team who created [GHTorrent](https://ghtorrent.org/). Their live mongodb service is no longer available, so I run locally with a few of their graciously provided [dumps](https://ghtorrent.org/downloads.html).

Currently I've pulled only the latest dump for simple testing. You can pull this dump as a `.tar.gz` [here](http://ghtorrent-downloads.ewi.tudelft.nl/mongo-daily/mongo-dump-2019-06-30.tar.gz). 

## Format
I've listed the total entries I have of each collection and the raw available keys below as a reference.

### commits - 768659
'_id', 'sha', 'node_id', 'commit', 'url', 'html_url', 'comments_url', 'author', 'committer', 'parents', 'stats', 'files', 'etag'

### events - 1060157
'_id', 'id', 'type', 'actor', 'repo', 'payload', 'public', 'created_at'

### forks - 29181
'_id', 'id', 'node_id', 'name', 'full_name', 'private', 'owner', 'html_url', 'description', 'fork', 'url', 'forks_url', 'keys_url', 'collaborators_url', 'teams_url', 'hooks_url', 'issue_events_url', 'events_url', 'assignees_url', 'branches_url', 'tags_url', 'blobs_url', 'git_tags_url', 'git_refs_url', 'trees_url', 'statuses_url', 'languages_url', 'stargazers_url', 'contributors_url', 'subscribers_url', 'subscription_url', 'commits_url', 'git_commits_url', 'comments_url', 'issue_comment_url', 'contents_url', 'compare_url', 'merges_url', 'archive_url', 'downloads_url', 'issues_url', 'pulls_url', 'milestones_url', 'notifications_url', 'labels_url', 'releases_url', 'deployments_url', 'created_at', 'updated_at', 'pushed_at', 'git_url', 'ssh_url', 'clone_url', 'svn_url', 'homepage', 'size', 'stargazers_count', 'watchers_count', 'language', 'has_issues', 'has_projects', 'has_downloads', 'has_wiki', 'has_pages', 'forks_count', 'mirror_url', 'archived', 'disabled', 'open_issues_count', 'license', 'forks', 'open_issues', 'watchers', 'default_branch', 'public', 'repo'

### geo_cache - 77
'_id', 'key', 'long', 'lat', 'city', 'country', 'state', 'country_code', 'status', 'updated_at'

### issue_comments - 46481
'_id', 'url', 'html_url', 'issue_url', 'id', 'node_id', 'user', 'created_at', 'updated_at', 'author_association', 'body', 'etag', 'repo', 'owner', 'issue_id'

### issue_events -55110
'_id', 'id', 'node_id', 'url', 'actor', 'event', 'commit_id', 'commit_url', 'created_at', 'label', 'owner', 'repo', 'issue_id'

### issues - 35950
'_id', 'url', 'repository_url', 'labels_url', 'comments_url', 'events_url', 'html_url', 'id', 'node_id', 'number', 'title', 'user', 'labels', 'state', 'locked', 'assignee', 'assignees', 'milestone', 'comments', 'created_at', 'updated_at', 'closed_at', 'author_association', 'body', 'closed_by', 'etag', 'repo', 'owner'

### org_members - 38
'_id', 'login', 'id', 'node_id', 'avatar_url', 'gravatar_id', 'url', 'html_url', 'followers_url', 'following_url', 'gists_url', 'starred_url', 'subscriptions_url', 'organizations_url', 'repos_url', 'events_url', 'received_events_url', 'type', 'site_admin', 'org'

### pull_request_comments - 11456


### pull_requests

### repo_collaborators

### repo_labels

### repos
'_id', 'id', 'node_id', 'name', 'full_name', 'private', 'owner', 'html_url', 'description', 'fork', 'url', 'forks_url', 'keys_url', 'collaborators_url', 'teams_url', 'hooks_url', 'issue_events_url', 'events_url', 'assignees_url', 'branches_url', 'tags_url', 'blobs_url', 'git_tags_url', 'git_refs_url', 'trees_url', 'statuses_url', 'languages_url', 'stargazers_url', 'contributors_url', 'subscribers_url', 'subscription_url', 'commits_url', 'git_commits_url', 'comments_url', 'issue_comment_url', 'contents_url', 'compare_url', 'merges_url', 'archive_url', 'downloads_url', 'issues_url', 'pulls_url', 'milestones_url', 'notifications_url', 'labels_url', 'releases_url', 'deployments_url', 'created_at', 'updated_at', 'pushed_at', 'git_url', 'ssh_url', 'clone_url', 'svn_url', 'homepage', 'size', 'stargazers_count', 'watchers_count', 'language', 'has_issues', 'has_projects', 'has_downloads', 'has_wiki', 'has_pages', 'forks_count', 'mirror_url', 'archived', 'disabled', 'open_issues_count', 'license', 'forks', 'open_issues', 'watchers', 'default_branch', 'permissions', 'network_count', 'subscribers_count', 'etag'

### topics

### users
'_id', 'login', 'id', 'node_id', 'avatar_url', 'gravatar_id', 'url', 'html_url', 'followers_url', 'following_url', 'gists_url', 'starred_url', 'subscriptions_url', 'organizations_url', 'repos_url', 'events_url', 'received_events_url', 'type', 'site_admin', 'name', 'company', 'blog', 'location', 'email', 'hireable', 'bio', 'public_repos', 'public_gists', 'followers', 'following', 'created_at', 'updated_at', 'etag'

### watchers