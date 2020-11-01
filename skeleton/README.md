# <%= (getf env :name) %><% @if description %> - <% @var description %><% @endif %>

## Usage

Shh... nothing to see here... yet...

## Installation
<%- @if author %>

## Author

* <% @var author %><% @if email %> (<% @var email %>)<% @endif %>

## Copyright

Copyright (c) <%= (local-time:timestamp-year (local-time:now)) %> <% @var author %><% @if email %> (<% @var email %>)<% @endif %>
<%- @endif %>
<%- @if license %>

## License

Licensed under the <% @var license %> License.
<%- @endif %>
