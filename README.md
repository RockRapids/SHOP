# Rock Rapids Community Applications Ecosystem

![Rock Rapids Logo](https://www.example.com/placeholder-for-rock-rapids-logo.png)

A suite of interconnected web applications designed to serve the Rock Rapids, Iowa community through easily maintainable, volunteer-driven technology solutions.

## Important Notice for Contributors

**This project is intended primarily for residents of Rock Rapids, Iowa and the surrounding area who can participate in physical meetings and activities within the community.** While the code is open source and you're welcome to fork it as a template for your own community, active contribution to this specific implementation requires local participation.

## About the Project

The Rock Rapids community applications ecosystem consists of eight interconnected web applications, each addressing specific aspects of community life:

- [Rockrapids.INFO](https://rockrapids.github.io/FOSS/0/): The central hub and gateway to all Rock Rapids applications
- [Rockrapids.ART](https://rockrapids.github.io/FOSS/1/): Showcasing local arts, crafts, and creative endeavors
- [Rockrapids.FUN](https://rockrapids.github.io/FOSS/2/): Highlighting recreational activities and entertainment options
- [Rockrapids.GUIDE](https://rockrapids.github.io/FOSS/3/): Providing civic, school, church, and service provider information
- [Rockrapids.SHOP](https://rockrapids.github.io/FOSS/4/): Featuring retail promotions and shopping events
- [Rockrapids.STORE](https://rockrapids.github.io/FOSS/5/): Listing marketplace items and local products for sale
- [Rockrapids.WORK](https://rockrapids.github.io/FOSS/6/): Connecting people with employment opportunities
- [Rockrapids.XYZ](https://rockrapids.github.io/FOSS/7/): Coordinating volunteer activities and recognition

## Design Philosophy

Our approach focuses on three core principles:

1. **Reuse what works**: We prioritize established, proven solutions rather than reinventing systems unnecessarily
2. **Connect and fill gaps**: We focus on integrating existing resources and addressing unmet needs
3. **Build for maintainability**: We create simple, sustainable solutions that future volunteers can easily maintain and improve

For a deeper understanding of our approach, please review these key documents:
- [Integrate Necessary Existing and Future Datastores](https://rockrapids.github.io/communication/2025/03/31/RockRapidsApps-Step0-1.html)
- [Design For Maintainability and Extensibility](https://rockrapids.github.io/communication/2025/03/31/RockRapidsApps-Step0-4.html)
- [Technical Architecture Overview](https://rockrapids.github.io/communication/2025/03/29/RockRapidsApps.html)

## Technical Architecture

The applications are built using:

- **Frontend Framework**: [Remix](https://remix.run/)
- **Data Management**: Polyglot persistence strategy (PostgreSQL, MongoDB, Redis)
- **Deployment**: [Fly.io](https://fly.io/)
- **Repository Structure**: Monorepo with shared packages

This architecture was selected for its maintainability, performance, and alignment with the skill sets available in our volunteer community.

## Getting Started

### For Users

Visit [RockRapids.INFO](https://rockrapids.info) to access the central hub for all Rock Rapids community applications.

### For Local Developers

1. Attend one of our monthly contributor meetings in Rock Rapids (see [RockRapids.INFO](https://rockrapids.info) for schedule)
2. Review our [Contributing Guidelines](CONTRIBUTING.md)
3. Set up your local development environment:

```bash
# Clone the repository
git clone https://github.com/rockrapids/community-apps.git

# Install dependencies
cd community-apps
npm install

# Start the development server
npm run dev
```

### For Communities Looking to Fork This Project

If you're interested in adapting this ecosystem for your own community:

1. Feel free to fork this repository
2. Customize the applications to meet your community's specific needs
3. Consider the maintenance requirements and ensure you have local volunteers who can sustain the system
4. We recommend preserving the design philosophy of simplicity and maintainability

## Contributing

This project is designed to be built and maintained by volunteers from the Rock Rapids community. If you're a resident of Rock Rapids or the surrounding area and would like to contribute, please:

1. Review our [Contributing Guidelines](CONTRIBUTING.md)
2. Familiarize yourself with our [Code of Conduct](CODE_OF_CONDUCT.md)
3. Join us at an upcoming in-person meeting or training session

We value local participation to ensure our applications truly serve the specific needs of Rock Rapids.

## Deployment

The applications are hosted on Fly.io, with detailed deployment instructions available in the [deployment documentation](docs/deployment.md).

## Project Status

This project is in active development. See the [Issues](https://github.com/rockrapids/community-apps/issues) page for current work items and the [Projects](https://github.com/rockrapids/community-apps/projects) page for our roadmap.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

We gratefully acknowledge the contributions of all Rock Rapids volunteers who have helped build and maintain these applications. Special thanks to:

- Our dedicated corps of volunteer developers and designers
- Community organizations who have provided feedback and testing

## Contact

Project Coordinator: Mark Bruns - [MarkBruns@MarkBruns.com](mailto:MarkBruns@MarkBruns.com)

For general inquiries, please attend one of our monthly community meetings (details on [RockRapids.INFO](https://rockrapids.info)).