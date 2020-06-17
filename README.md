# SIGNER-PDF

###### version 1.0

## System Requirements

- Java 8 (JDK 1.8)
- Maven 3

## FIRMANDO DIGITALMENTE DOCUMENTOS CON API JAVA

```bash
.
├── main
│   ├── java
│   │   └── com
│   │       └── groupdocs
│   │           └── ui
│   │               ├── Application.java
│   │               ├── ApplicationStartup.java
│   │               ├── ServerPortCustomizer.java
│   │               ├── config
│   │               │   ├── ApplicationConfiguration.java
│   │               │   ├── CommonConfiguration.java
│   │               │   ├── DefaultDirectories.java
│   │               │   ├── GlobalConfiguration.java
│   │               │   └── ServerConfiguration.java
│   │               ├── exception
│   │               │   ├── GroupDocsExceptionHandler.java
│   │               │   ├── PasswordExceptions.java
│   │               │   └── TotalGroupDocsException.java
│   │               ├── model
│   │               │   ├── request
│   │               │   │   ├── FileTreeRequest.java
│   │               │   │   ├── LoadDocumentPageRequest.java
│   │               │   │   └── LoadDocumentRequest.java
│   │               │   └── response
│   │               │       ├── ExceptionEntity.java
│   │               │       ├── FileDescriptionEntity.java
│   │               │       ├── LoadDocumentEntity.java
│   │               │       ├── PageDescriptionEntity.java
│   │               │       └── UploadedDocumentEntity.java
│   │               ├── signature
│   │               │   ├── SignatureConfiguration.java
│   │               │   ├── SignatureController.java
│   │               │   ├── SignatureLoader.java
│   │               │   ├── SignatureType.java
│   │               │   ├── XMLReaderWriter.java
│   │               │   ├── model
│   │               │   │   ├── request
│   │               │   │   │   ├── DeleteSignatureFileRequest.java
│   │               │   │   │   ├── LoadSignatureImageRequest.java
│   │               │   │   │   ├── SaveImageRequest.java
│   │               │   │   │   ├── SaveOpticalCodeRequest.java
│   │               │   │   │   ├── SaveStampRequest.java
│   │               │   │   │   ├── SaveTextRequest.java
│   │               │   │   │   ├── SignDocumentRequest.java
│   │               │   │   │   └── SignatureFileTreeRequest.java
│   │               │   │   ├── web
│   │               │   │   │   ├── SignatureDataEntity.java
│   │               │   │   │   ├── SignatureFileDescriptionEntity.java
│   │               │   │   │   ├── SignaturePageEntity.java
│   │               │   │   │   └── SignedDocumentEntity.java
│   │               │   │   └── xml
│   │               │   │       ├── OpticalXmlEntity.java
│   │               │   │       ├── StampXmlEntity.java
│   │               │   │       ├── StampXmlEntityList.java
│   │               │   │       ├── TextXmlEntity.java
│   │               │   │       ├── XmlEntity.java
│   │               │   │       └── XmlEntityWithImage.java
│   │               │   ├── service
│   │               │   │   ├── SaveSignatureService.java
│   │               │   │   ├── SaveSignatureServiceImpl.java
│   │               │   │   ├── SignService.java
│   │               │   │   ├── SignServiceImpl.java
│   │               │   │   ├── SignatureHandlerFactory.java
│   │               │   │   ├── SignatureService.java
│   │               │   │   ├── SignatureServiceImpl.java
│   │               │   │   └── SortedSignaturesData.java
│   │               │   └── signer
│   │               │       ├── BarCodeSigner.java
│   │               │       ├── DigitalSigner.java
│   │               │       ├── ImageSigner.java
│   │               │       ├── QrCodeSigner.java
│   │               │       ├── Signer.java
│   │               │       ├── StampSigner.java
│   │               │       └── TextSigner.java
│   │               └── util
│   │                   ├── Utils.java
│   │                   └── directory
│   │                       ├── PathConstants.java
│   │                       └── SignatureDirectory.java
│   ├── resources
│   │   ├── application.properties
│   │   ├── defaultConfiguration.yml
│   │   ├── static
│   │   │   └── angular
│   │   │       └── signature
│   │   │           ├── favicon.ico
│   │   │           ├── index.html
│   │   │           ├── main-es2015.js
│   │   │           ├── main-es2015.js.map
│   │   │           ├── main-es5.js
│   │   │           ├── main-es5.js.map
│   │   │           ├── polyfills-es2015.js
│   │   │           ├── polyfills-es2015.js.map
│   │   │           ├── polyfills-es5.js
│   │   │           ├── polyfills-es5.js.map
│   │   │           ├── runtime-es2015.js
│   │   │           ├── runtime-es2015.js.map
│   │   │           ├── runtime-es5.js
│   │   │           ├── runtime-es5.js.map
│   │   │           ├── styles-es2015.js
│   │   │           ├── styles-es2015.js.map
│   │   │           ├── styles-es5.js
│   │   │           ├── styles-es5.js.map
│   │   │           ├── vendor-es2015.js
│   │   │           ├── vendor-es2015.js.map
│   │   │           ├── vendor-es5.js
│   │   │           └── vendor-es5.js.map
│   │   └── templates
│   │       └── signature.html
│   └── webapp
│       └── META-INF
│           └── context.xml
└── test
    └── java
        └── com
            └── groupdocs
                └── ui
                    └── signature
                        └── SignatureControllerTest.java
```

SIGNER-PDF permite firmar digitalmente Archivos **add PDF, DOCX, PPT, XLS**. Utilizando una poderosa y flexible API para firmar manualmente, codigo de barra, QR code, Imagen y Firma estampada al documento.

## Demo Video

<p align="center">
  <a title="Document signature for JAVA " href="https://youtu.be/MakhcqlV7iQ"> 
    <img src="https://raw.githubusercontent.com/groupdocs-signature/groupdocs-signature.github.io/master/resources/image/document-signature-demo.gif" width="100%" style="width:100%;">
  </a>
</p>

## Features

<p>
<img src="https://raw.githubusercontent.com/groupdocs-signature/groupdocs-signature.github.io/master/resources/image/responsive.png?v=1" align="left" width="430"/>
<br/><br/><br/>
  <b>Responsive</b>
<div>Unique experience on the mobile device. Draw signature with your finger in landscape mode.</div>
<br/><br/><br/><br/>
</p>
<br/>
<p>
<img src="https://raw.githubusercontent.com/groupdocs-signature/groupdocs-signature.github.io/master/resources/image/digital-signature.png?v=1" align="left" width="430"/>
<br/><br/><br/>
  <b>Digital certificate</b>
<div>Add digital signature to securely sign documents.</div>
<br/><br/><br/>
</p>
<br/>
<p>
<img src="https://raw.githubusercontent.com/groupdocs-signature/groupdocs-signature.github.io/master/resources/image/barcode-generator.png?v=1" align="left" width="430"/>
<br/><br/><br/>
  <b>Barcode generator</b>
<div>Embedded barcode generator can generate over 50 barcode symbologies including linear, 2D and postal barcodes.</div>
<br/><br/><br/><br/>
</p>
<br/>
<p>
<img src="https://raw.githubusercontent.com/groupdocs-signature/groupdocs-signature.github.io/master/resources/image/qr-code-generator.png?v=1" align="left" width="430"/>
<br/><br/><br/>
  <b>QR code generator</b>
<div>Embeded QR generator can generate PDF417, MacroPDF417, DataMatrix, Aztec, QR, Italian Post 25, GS1DataMatrix 2D barcodes.</div>
<br/><br/><br/><br/><br/><br/>
</p>
<hr/>

### More features

- Clean, modern and intuitive design
- Easily switchable colour theme (create your own colour theme in 5 minutes)
- Responsive design
- Mobile support (open application on any mobile device)
- Support over 50 documents and image formats
- Image mode
- Fully customizable navigation panel
- Sign password protected documents
- Download original documents
- Download signed documents
- Upload documents
- Upload signatures
- Sign document with such signature types: digital certificate, image, stamp, qrCode, barCode.
- Draw signature image
- Draw stamp signature
- Generate bar code signature
- Generate qr code signature
- Print document
- Smooth page navigation
- Smooth document scrolling
- Preload pages for faster document rendering
- Multi-language support for displaying errors
- Cross-browser support (Safari, Chrome, Opera, Firefox)
- Cross-platform support (Windows, Linux, MacOS)

## How to run

Tu puedes ejecutar este aplicativo por medio de los siguientes métodos

#### Build from source

```bash
mvn clean spring-boot:run
```

#### Build war from source

```bash
mvn package -P war
## Deploy this war on any server
```

## Configuration

Ajustes se realizan en `configuration.yml`.

### Signature configuration options

| Option                 | Type    |   Default value   | Description                                                                                                                                  |
| ---------------------- | ------- | :---------------: | :------------------------------------------------------------------------------------------------------------------------------------------- |
| **`filesDirectory`**   | String  | `DocumentSamples` | Files directory path. Indicates where uploaded and predefined files are stored. It can be absolute or relative path                          |
| **`fontsDirectory`**   | String  |                   | Path to custom fonts directory.                                                                                                              |
| **`defaultDocument`**  | String  |                   | Absolute path to default document that will be loaded automaticaly.                                                                          |
| **`preloadPageCount`** | Integer |        `0`        | Indicate how many pages from a document should be loaded, remaining pages will be loaded on page scrolling.Set `0` to load all pages at once |
| **`textSignature`**    | Boolean |      `true`       | Enable/disable text signature                                                                                                                |
| **`imageSignature`**   | Boolean |      `true`       | Enable/disable image signature                                                                                                               |
| **`digitalSignature`** | Boolean |      `true`       | Enable/disable digital signature                                                                                                             |
| **`qrCodeSignature`**  | Boolean |      `true`       | Enable/disable QR-Code signature                                                                                                             |
| **`barCodeSignature`** | Boolean |      `true`       | Enable/disable Barcode signature                                                                                                             |
| **`stampSignature`**   | Boolean |      `true`       | Enable/disable Stamp signature                                                                                                               |
| **`handSignature`**    | Boolean |      `true`       | Enable/disable Hand signature                                                                                                                |
| **`downloadOriginal`** | Boolean |      `true`       | Enable/disable original document downloading                                                                                                 |
| **`downloadSigned`**   | Boolean |      `true`       | Enable/disable signed document downloading                                                                                                   |
