# pihole-twitter (pihole-x)

X (formerly known as Twitter) DNS Blocklist for Pihole. This list blocks X (formerly known as Twitter) in it's entirety, not just ads or tracking served by X (formerly known as Twitter).

```
https://raw.githubusercontent.com/JackCuthbert/pihole-twitter/main/pihole-twitter.txt
```

## Usage

### Pi-Hole

1. Login into Pi-hole admin
2. Navigate to "Adlists"
3. Copy this URL: `https://raw.githubusercontent.com/JackCuthbert/pihole-twitter/main/pihole-twitter.txt`
4. Paste the URL in the address box and click on Add

### AdguardHome

1. Login to AdguardHome admin
2. Navigate to Filters > DNS Blocklists
3. Click "Add blocklist" at the bottom
4. Select "Add a custom list"
5. Enter a name like `pihole-twitter`
6. Enter this url: `https://raw.githubusercontent.com/JackCuthbert/pihole-twitter/main/pihole-twitter.txt`
7. Click "Save"

## Other lists

I sometimes maintain other lists:

- [pihole-reddit](https://github.com/JackCuthbert/pihole-reddit): Block Reddit domains.
- [pihole-splogs](https://github.com/JackCuthbert/pihole-splogs): Block low value GitHub or Stack Overflow spam blogs.
- [pihole-ausnews](https://github.com/JackCuthbert/pihole-ausnews): Block non-Murdoch owned Australian News sites and services.
