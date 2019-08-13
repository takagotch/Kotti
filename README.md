### kotti
---
http://kotti.pylonsproject.org/

```py
pyramid.includes = kotti_twitter.include_profile_widget

kotti_twitter.profile_widget.uer = douri
kotti_twitter.profile_widget.loop = true

pyramid.includes =
  kotti_twitter.include_search_widget
  kotti_twitter.include_profile_widget
  
kotti.available_types = kotti.resources.Document kotti.resources.File

kotti.available_type =
  kotti.resources.Document
  kotti_calendar.resources.Calendar
  kotti_calendar.resources.Event
  
kotti.populators = kotti.populate.populate

kotti.search_content = kotti.views.util.default_search_content

pyramid.default_locale_name = en

pyramid.default_locale_name = de_DE

kotti.authn_policy_factory = kotti.authkt_factory
kotti.authz_policy_factory = kotti.acl_factory

kotti.caching_policy_chooser = kotti.views.cache.default_caching_policy_chooser

kotti.url_normalzier = kotti.url_normalizer.url_normalizer
kotti.url_normalizer.map_non_ascii_characters = True

pyramid.includes = kotti.views.slots.includeme_local_navigation
pyramid.includes = kotti_navigation.include_nabigation_widget
```

```
```

```
```


