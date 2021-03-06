# interview

## Challenge

A Holiday gift exchange is where a group of people are randomly assigned one other person in the group to buy a gift for. This person can be anyone else in the group except for themselves. Everyone should both give and receive a gift.

Design a program that reads a provided CSV file, performs the matching, and then prints out the matches. Assume that you may email the match to the person later, but focus on printing first.

The format of the CSV is name,email on each row.

Don't actually send email for this example. Assume the system or framework has a mail delivery system available.

Sample input files provided:

```csv
Chris,chris@example.com
Felix,felix@example.net
Elizabeth,lizzy1994@example.com
André,andre@example.fr
Milo,milo.milo@example.com
Olivia,olive99@example.net
Hugo,hugo124@example.net
Amit,amit.123@example.com
Ludwig,ludwig@example.net
Raoul,raoul@example.com
```


## Installation

1. Add the dependency to your `shard.yml`:

   ```yaml
   dependencies:
     interview:
       github: grepsedawk/interview.cr
   ```

2. Run `shards install`

## Usage

```crystal
require "interview"
```

TODO: Write usage instructions here

## Development

TODO: Write development instructions here

## Contributing

1. Fork it (<https://github.com/grepsedawk/interview.cr/fork>)
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request

## Contributors

- [grepsedawk](https://github.com/grepsedawk) - creator and maintainer
