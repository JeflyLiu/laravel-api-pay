# 账户

- [获取所有账户](#获取所有账户)
- [获取认证账户](#获取认证账户)
- [获取指定账户](#获取指定账户)
- [获取账户交易记录](#获取账户交易记录)
- [添加账户](#添加账户)
- [修改指定账户](#修改指定账户)
- [删除指定账户](#删除指定账户)

## 获取所有账户

    GET /accounts

参数

Name    |Type     |Description
----    |----     |----
since   |string   |The integer ID of the last User that you’ve seen.


响应

    Status: 200 OK
    X-RateLimit-Limit: 5000
    X-RateLimit-Remaining: 4999

    [
      {
        "login": "octocat",
        "id": 1,
        "avatar_url": "https://github.com/images/error/octocat_happy.gif",
        "gravatar_id": "somehexcode",
        "url": "https://api.github.com/users/octocat",
        "html_url": "https://github.com/octocat",
        "followers_url": "https://api.github.com/users/octocat/followers",
        "following_url": "https://api.github.com/users/octocat/following{/other_user}",
        "gists_url": "https://api.github.com/users/octocat/gists{/gist_id}",
        "starred_url": "https://api.github.com/users/octocat/starred{/owner}{/repo}",
        "subscriptions_url": "https://api.github.com/users/octocat/subscriptions",
        "organizations_url": "https://api.github.com/users/octocat/orgs",
        "repos_url": "https://api.github.com/users/octocat/repos",
        "events_url": "https://api.github.com/users/octocat/events{/privacy}",
        "received_events_url": "https://api.github.com/users/octocat/received_events",
        "type": "User",
        "site_admin": false
      }
    ]

## 获取认证账户

## 获取指定账户

## 获取账户交易记录

## 添加账户

## 修改指定账户 

## 删除指定账户