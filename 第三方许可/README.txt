Local browser QR assets

qrcode-generator 2.0.4 (Kazuhiko Arase), MIT license.
jsQR 1.4.0 (Cosmo Wolfe and contributors), Apache-2.0 license.

Copied unmodified from official GitHub repositories. Files are locally fixed and verified by the SHA256 values below. No runtime CDN dependency.
Include qrcode.js and jsQR.js via local script tags.

Browser API:
const qr = qrcode(0, "M");
qr.addData(url);
qr.make();
const svg = qr.createSvgTag({cellSize: 8, margin: 32, scalable: true});
const found = jsQR(imageData.data, imageData.width, imageData.height);
const decodedText = found ? found.data : null;

Official API references:
https://github.com/kazuhikoarase/qrcode-generator/blob/master/js/README.md
https://github.com/cozmo/jsQR#usage

Source provenance:
[
  {
    "file": "qrcode.js",
    "source": "https://raw.githubusercontent.com/kazuhikoarase/qrcode-generator/master/js/dist/qrcode.js",
    "bytes": 56694,
    "sha256": "79ec86f82856005b1c887905cfccfcfbec3821ca61c7fd5a952faa5f778f791c"
  },
  {
    "file": "LICENSE-qrcode-generator.txt",
    "source": "https://raw.githubusercontent.com/kazuhikoarase/qrcode-generator/master/LICENSE",
    "bytes": 1071,
    "sha256": "3a850fa5f08101db6f40676c2786e10bd2cd5fff7b12ffdf1e0c434d4e49d90c"
  },
  {
    "file": "jsQR.js",
    "source": "https://raw.githubusercontent.com/cozmo/jsQR/master/dist/jsQR.js",
    "bytes": 256723,
    "sha256": "3325b0888fa4745c4e6940897d8c4f426fbaae76901fcbfe1871a04e90a51655"
  },
  {
    "file": "LICENSE-jsQR.txt",
    "source": "https://raw.githubusercontent.com/cozmo/jsQR/master/LICENSE",
    "bytes": 11358,
    "sha256": "c6596eb7be8581c18be736c846fb9173b69eccf6ef94c5135893ec56bd92ba08"
  }
]
