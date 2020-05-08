# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [4.1.1] - 2020-5-8
### Added
- Custom domain name for Image Handler distribution
- Custom domain name for DemoUI distribution
- SSL certificate support for Image Handler distribution
- SSL certificate support for DemoUI distribution
- CloudFront AOI support for DemoUI distribution

### Removed
- Public access to S3 object

## [4.1] - 2019-12-31
### Added
- CHANGELOG file
- Access logging to API Gateway

### Changed
- Lambda functions runtime to nodejs12.x
- sharp version (from 0.21.3 to 0.23.3)
- Image handler function to use Composite API (https://sharp.pixelplumbing.com/en/stable/api-composite/)
- License to Apache-2.0

### Removed
- Reference to deprecated sharp function (overlayWith)
