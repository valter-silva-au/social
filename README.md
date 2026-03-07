# social

My [git-social](https://github.com/valter-silva-au/git-social) repository. A decentralized social profile where every post is a JSON file and every identity is a Git repo.

## Structure

- `profile.json` - My identity and public info
- `following.json` - Users I follow
- `feed-index.json` - Manifest of all posts for efficient fetching
- `posts/YYYY/MM/DD/*.json` - Individual posts, date-partitioned
