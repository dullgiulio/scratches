Pros
----

- Recognizing pictures is not impossible, but relatively hard. This goes away with it.

Cons
----

- Can fashion be this straightforward? Maybe some people appreciate it.

Data Models
-----------

- Clothing pieces
  - Photo
  - Fauceted tags

- Faceted tags:
  - goes-with
  - avoid-with
  - use-at
  - ...

- Tags on top are more important than tags at the bottom

Examples:

- Chinos
  - Pictures...
  - Tags:
    - is
      - chinos
      - trousers
    - goes-with
      - t-shirt
      - classic-jacket
      - belt
    - use-at
      - casual-party
      - work

- Classic-jacket
  - Pictures...
  - Tags:
    - is
       - classic-jacket
    - goes-with
       - suit
       - chinos
    - avoid-with
       - swimming-pants
    - use-at
       - social-event

* TODO: Color combinations as tags?

Actions
-------

. User Add

* User send a picture of a clothing item
* User can optionally provide tags
* User can optionally make the item public
* Picture is approved and tags edited

. User Select

* User can generate a random pairing
  - between owned items that go together
  - owned items suitable for a specific social occasion ("use-at")

* TODO: Take into accounts color combinations!

. User Suggestion

* Show items a user doesn't have but go well with owned items. 
