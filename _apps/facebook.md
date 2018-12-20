---
slug: facebook
---
# Facebook

When Facebook isn't busy selling your data to
[corporations](https://www.nytimes.com/2018/12/18/technology/facebook-privacy.html),
they make it available to you.

* Sign in to [Facebook](https://facebook.com/)
* Go to [Settings](https://www.facebook.com/settings)
* Select [Your Facebook Infomation](https://www.facebook.com/settings?tab=your_facebook_information) from the left menu
* Next to "Download Your Information" press "View"
* Select "JSON" as the format
* Select "High" as the media quality
* Press "Create File"

An email will arrive in your inbox once your archive is ready to download.

## Archive Contents

```
├── about_you
│   ├── friend_peer_group.json
│   └── your_address_books.json
├── ads
│   ├── ads_interests.json
│   ├── advertisers_who_uploaded_a_contact_list_with_your_information.json
│   └── advertisers_you've_interacted_with.json
├── apps
│   ├── installed_apps.json
│   ├── posts_from_apps.json
│   └── your_apps.json
├── calls_and_messages
│   └── calls_and_messages.json
├── comments
│   └── comments.json
├── events
│   ├── event_invitations.json
│   ├── event_responses.json
│   └── your_events.json
├── following_and_followers
│   └── followed_pages.json
├── friends
│   ├── friends_added.json
│   ├── rejected_friend_requests.json
│   ├── removed_friends.json
│   └── sent_friend_requests.json
├── groups
│   ├── groups_you_manage.json
│   ├── your_group_membership_activity.json
│   └── your_posts_and_comments_in_groups.json
├── likes_and_reactions
│   ├── pages.json
│   └── posts_and_comments.json
├── location_history
│   └── your_location_history.json
├── marketplace
│   └── no-data.txt
├── messages
│   ├── <:id>
│   │   ├── gifs/
│   │   ├── message.json
│   │   └── photos/
│   └── ...
├── network_information
│   └── network_information.json
├── other_activity
│   ├── fundraisers_donated_to.json
│   ├── pokes.json
│   └── polls_you_voted_on.json
├── pages
│   └── your_pages.json
├── payment_history
│   └── payment_history.json
├── photos
│   ├── photos.json
│   └── <:album>
│       └── *.jpg
├── posts
│   ├── other_people's_posts_to_your_timeline.json
│   └── your_posts.json
├── profile_information
│   ├── profile_information.json
│   └── profile_update_history.json
├── saved_items
│   └── your_saved_items.json
├── search_history
│   └── your_search_history.json
├── security_and_login_information
│   ├── account_activity.json
│   ├── account_status_changes.json
│   ├── administrative_records.json
│   ├── authorized_logins.json
│   ├── login_protection_data.json
│   ├── logins_and_logouts.json
│   ├── used_ip_addresses.json
│   └── where_you're_logged_in.json
├── videos
│   ├── *.mp4
│   ├── thumbnails
│   │   └── *.jpg
│   └── videos.json
└── your_places
    └── no-data.txt
```
