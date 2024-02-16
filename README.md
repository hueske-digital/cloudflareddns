The value of CF_API_TOKEN should be an API token (not an API key), which can be obtained from the API Tokens page. Use the Edit zone DNS template to create and copy a token into the environment file. (The less secure API key authentication is deliberately not supported.)

The value of DOMAINS should be a list of fully qualified domain names (FQDNs) separated by commas. For example, DOMAINS=example.org,www.example.org,example.io instructs the updater to manage the domains example.org, www.example.org, and example.io. These domains do not have to be in the same zone---the updater will identify their zones automatically.

See more here: https://github.com/favonia/cloudflare-ddns?tab=readme-ov-file#%EF%B8%8F-further-customization
