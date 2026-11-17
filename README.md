# website

![Jesus Graterol portfolio](./readme-assets/screenshot-01.png)

The source for [jesusgraterol.dev](https://jesusgraterol.dev/), the static portfolio of seasoned Software Developer Jesus Graterol. It presents selected projects, professional experience, education, and the complete technology stack in a fast, accessible single-page site.

## Project blueprint

| Task                                                 | Documentation                                                                                                               |
| ---------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| Set up the site, change content or regenerate assets | [Development](docs/development.md), including source ownership, commands, the machine-readable portfolio and SEO output.    |
| Choose verification                                  | [Testing](docs/testing.md), covering essential/full selections, focused checks, privacy and production-artifact guarantees. |
| Understand Pages and Cloudflare publishing           | [Publishing](docs/development.md#publishing), with the custom-domain and edge responsibility boundary.                      |
| Integrate or deliver changes                         | [Delivery](docs/delivery.md), defining development/main stops, remote containment and deployed-artifact verification.       |

`src/data/portfolio/` owns validated content; `src/components/` and `src/layouts/` render the site using `jg-personal-astro-ui`. `src/utilities/` owns discovery and structured data, and `scripts/` validates output and generates assets. `docs/` holds concise durable guides; API and endpoint references belong with their established owners outside it.

## License

[MIT](./LICENSE)
