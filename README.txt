ABOUT

It's often useful to provide two versions of a given string: one that's
intended for human viewing and another that's intended for use in database
queries, URLs, and so on. In Drupal, this is generally known as a 'Name' and
'Machine name' pair. Drupal 7 even provides a prefab FormAPI element to simplify
the process of entering these matched pairs.

Safeword exposes a custom FieldAPI field type that stores two strings using the
name/machine name approach. It can be useful when generating PathAuto aliases,
exposing Views arguments, and so on.