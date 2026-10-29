# README icons

Brand logos are stored locally so the profile README does not depend on third-party image hosts at render time.

## Sources

- [Devicon v2.17.0](https://github.com/devicons/devicon/tree/v2.17.0/icons): development, database, messaging, cloud, and frontend logos. MIT license in `LICENSE`.
- [Simple Icons v13.0.0](https://github.com/simple-icons/simple-icons/tree/13.0.0/icons): Strapi, LangChain, and Meilisearch. CC0 license in `SIMPLE-ICONS-LICENSE`.
- [Microsoft SharePoint product icon](https://static2.sharepointonline.com/files/fabric/assets/brand-icons/product/svg/sharepoint_48x1.svg).
- [Bull official repository](https://github.com/OptimalBits/bull/blob/develop/support/logo.svg). MIT license in `BULL-LICENSE`.
- [VMware Workstation icon on Wikimedia Commons](https://commons.wikimedia.org/wiki/File:VMware_Workstation_11.0_icon.png).

## Display adjustments

SVG root dimensions are set to 50 × 50 so Markdown previews that override image height still render compact icons. Rust, Kafka, AWS, and LangChain have variants for dark backgrounds.

Microservices, event-driven architecture, distributed systems, API design, WebSockets, CI/CD, and AI integration use custom SVG illustrations. These depict concepts and are not brand logos.

Architecture illustrations use compact geometric symbols: connected service cubes, an event source with outgoing signal waves, a distributed mesh of nodes, faceted code brackets, and paired arrows for a two-way connection.

AI integration uses a two-tone purple and cyan brain with neural connections, replacing the earlier processor illustration.

Custom concept icons use transparent backgrounds and flat colors to match the surrounding technology logos. Related light, mid, and dark tones add depth without gradients or shadows.

The six custom icons share a 64 × 64 viewBox and render at 50 × 50 in the README. Their silhouettes avoid small lettering so they remain legible at that size on light and dark backgrounds.

The revised concept SVG filenames use `-v2.svg` so GitHub requests fresh images after the redesign instead of reusing the cached originals.
