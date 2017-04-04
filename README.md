# api documentation for  [http-errors (v1.6.1)](https://github.com/jshttp/http-errors#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-http-errors.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-http-errors) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-http-errors.svg)](https://travis-ci.org/npmdoc/node-npmdoc-http-errors)
#### Create HTTP error objects

[![NPM](https://nodei.co/npm/http-errors.png?downloads=true)](https://www.npmjs.com/package/http-errors)

[![apidoc](https://npmdoc.github.io/node-npmdoc-http-errors/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-http-errors_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-http-errors/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-http-errors/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-http-errors/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jonathan Ong",
        "email": "me@jongleberry.com",
        "url": "http://jongleberry.com"
    },
    "bugs": {
        "url": "https://github.com/jshttp/http-errors/issues"
    },
    "contributors": [
        {
            "name": "Alan Plum",
            "email": "me@pluma.io"
        },
        {
            "name": "Douglas Christopher Wilson",
            "email": "doug@somethingdoug.com"
        }
    ],
    "dependencies": {
        "depd": "1.1.0",
        "inherits": "2.0.3",
        "setprototypeof": "1.0.3",
        "statuses": ">= 1.3.1 < 2"
    },
    "description": "Create HTTP error objects",
    "devDependencies": {
        "eslint": "3.16.0",
        "eslint-config-standard": "6.2.1",
        "eslint-plugin-markdown": "1.0.0-beta.3",
        "eslint-plugin-promise": "3.4.2",
        "eslint-plugin-standard": "2.0.1",
        "istanbul": "0.4.5",
        "mocha": "1.21.5"
    },
    "directories": {},
    "dist": {
        "shasum": "5f8b8ed98aca545656bf572997387f904a722257",
        "tarball": "https://registry.npmjs.org/http-errors/-/http-errors-1.6.1.tgz"
    },
    "engines": {
        "node": ">= 0.6"
    },
    "files": [
        "index.js",
        "HISTORY.md",
        "LICENSE",
        "README.md"
    ],
    "gitHead": "d8d95dbc84c913a594b7fca07096697412af7edd",
    "homepage": "https://github.com/jshttp/http-errors#readme",
    "keywords": [
        "http",
        "error"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "dougwilson",
            "email": "doug@somethingdoug.com"
        },
        {
            "name": "egeste",
            "email": "npm@egeste.net"
        },
        {
            "name": "jongleberry",
            "email": "jonathanrichardong@gmail.com"
        }
    ],
    "name": "http-errors",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jshttp/http-errors.git"
    },
    "scripts": {
        "lint": "eslint --plugin markdown --ext js,md .",
        "test": "mocha --reporter spec --bail",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter dot"
    },
    "version": "1.6.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module http-errors](#apidoc.module.http-errors)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>400 (message)](#apidoc.element.http-errors.400)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>401 (message)](#apidoc.element.http-errors.401)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>402 (message)](#apidoc.element.http-errors.402)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>403 (message)](#apidoc.element.http-errors.403)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>404 (message)](#apidoc.element.http-errors.404)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>405 (message)](#apidoc.element.http-errors.405)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>406 (message)](#apidoc.element.http-errors.406)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>407 (message)](#apidoc.element.http-errors.407)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>408 (message)](#apidoc.element.http-errors.408)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>409 (message)](#apidoc.element.http-errors.409)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>410 (message)](#apidoc.element.http-errors.410)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>411 (message)](#apidoc.element.http-errors.411)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>412 (message)](#apidoc.element.http-errors.412)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>413 (message)](#apidoc.element.http-errors.413)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>414 (message)](#apidoc.element.http-errors.414)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>415 (message)](#apidoc.element.http-errors.415)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>416 (message)](#apidoc.element.http-errors.416)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>417 (message)](#apidoc.element.http-errors.417)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>418 (message)](#apidoc.element.http-errors.418)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>421 (message)](#apidoc.element.http-errors.421)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>422 (message)](#apidoc.element.http-errors.422)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>423 (message)](#apidoc.element.http-errors.423)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>424 (message)](#apidoc.element.http-errors.424)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>425 (message)](#apidoc.element.http-errors.425)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>426 (message)](#apidoc.element.http-errors.426)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>428 (message)](#apidoc.element.http-errors.428)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>429 (message)](#apidoc.element.http-errors.429)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>431 (message)](#apidoc.element.http-errors.431)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>451 (message)](#apidoc.element.http-errors.451)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>500 (message)](#apidoc.element.http-errors.500)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>501 (message)](#apidoc.element.http-errors.501)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>502 (message)](#apidoc.element.http-errors.502)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>503 (message)](#apidoc.element.http-errors.503)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>504 (message)](#apidoc.element.http-errors.504)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>505 (message)](#apidoc.element.http-errors.505)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>506 (message)](#apidoc.element.http-errors.506)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>507 (message)](#apidoc.element.http-errors.507)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>508 (message)](#apidoc.element.http-errors.508)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>509 (message)](#apidoc.element.http-errors.509)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>510 (message)](#apidoc.element.http-errors.510)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>511 (message)](#apidoc.element.http-errors.511)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>BadGateway (message)](#apidoc.element.http-errors.BadGateway)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>BadRequest (message)](#apidoc.element.http-errors.BadRequest)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>BandwidthLimitExceeded (message)](#apidoc.element.http-errors.BandwidthLimitExceeded)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>Conflict (message)](#apidoc.element.http-errors.Conflict)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>ExpectationFailed (message)](#apidoc.element.http-errors.ExpectationFailed)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>FailedDependency (message)](#apidoc.element.http-errors.FailedDependency)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>Forbidden (message)](#apidoc.element.http-errors.Forbidden)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>GatewayTimeout (message)](#apidoc.element.http-errors.GatewayTimeout)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>Gone (message)](#apidoc.element.http-errors.Gone)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>HTTPVersionNotSupported (message)](#apidoc.element.http-errors.HTTPVersionNotSupported)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>HttpError ()](#apidoc.element.http-errors.HttpError)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>HttpError.super_ ()](#apidoc.element.http-errors.HttpError.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>ImATeapot (message)](#apidoc.element.http-errors.ImATeapot)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>InsufficientStorage (message)](#apidoc.element.http-errors.InsufficientStorage)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>InternalServerError (message)](#apidoc.element.http-errors.InternalServerError)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>LengthRequired (message)](#apidoc.element.http-errors.LengthRequired)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>Locked (message)](#apidoc.element.http-errors.Locked)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>LoopDetected (message)](#apidoc.element.http-errors.LoopDetected)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>MethodNotAllowed (message)](#apidoc.element.http-errors.MethodNotAllowed)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>MisdirectedRequest (message)](#apidoc.element.http-errors.MisdirectedRequest)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>NetworkAuthenticationRequired (message)](#apidoc.element.http-errors.NetworkAuthenticationRequired)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>NotAcceptable (message)](#apidoc.element.http-errors.NotAcceptable)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>NotExtended (message)](#apidoc.element.http-errors.NotExtended)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>NotFound (message)](#apidoc.element.http-errors.NotFound)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>NotImplemented (message)](#apidoc.element.http-errors.NotImplemented)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>PayloadTooLarge (message)](#apidoc.element.http-errors.PayloadTooLarge)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>PaymentRequired (message)](#apidoc.element.http-errors.PaymentRequired)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>PreconditionFailed (message)](#apidoc.element.http-errors.PreconditionFailed)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>PreconditionRequired (message)](#apidoc.element.http-errors.PreconditionRequired)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>ProxyAuthenticationRequired (message)](#apidoc.element.http-errors.ProxyAuthenticationRequired)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>RangeNotSatisfiable (message)](#apidoc.element.http-errors.RangeNotSatisfiable)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>RequestHeaderFieldsTooLarge (message)](#apidoc.element.http-errors.RequestHeaderFieldsTooLarge)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>RequestTimeout (message)](#apidoc.element.http-errors.RequestTimeout)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>ServiceUnavailable (message)](#apidoc.element.http-errors.ServiceUnavailable)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>TooManyRequests (message)](#apidoc.element.http-errors.TooManyRequests)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>URITooLong (message)](#apidoc.element.http-errors.URITooLong)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>Unauthorized (message)](#apidoc.element.http-errors.Unauthorized)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>UnavailableForLegalReasons (message)](#apidoc.element.http-errors.UnavailableForLegalReasons)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>UnorderedCollection (message)](#apidoc.element.http-errors.UnorderedCollection)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>UnprocessableEntity (message)](#apidoc.element.http-errors.UnprocessableEntity)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>UnsupportedMediaType (message)](#apidoc.element.http-errors.UnsupportedMediaType)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>UpgradeRequired (message)](#apidoc.element.http-errors.UpgradeRequired)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>VariantAlsoNegotiates (message)](#apidoc.element.http-errors.VariantAlsoNegotiates)

#### [module http-errors.400](#apidoc.module.http-errors.400)
1.  [function <span class="apidocSignatureSpan">http-errors.400.</span>super_ ()](#apidoc.element.http-errors.400.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>400 (message)](#apidoc.element.http-errors.400.400)

#### [module http-errors.401](#apidoc.module.http-errors.401)
1.  [function <span class="apidocSignatureSpan">http-errors.401.</span>super_ ()](#apidoc.element.http-errors.401.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>401 (message)](#apidoc.element.http-errors.401.401)

#### [module http-errors.402](#apidoc.module.http-errors.402)
1.  [function <span class="apidocSignatureSpan">http-errors.402.</span>super_ ()](#apidoc.element.http-errors.402.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>402 (message)](#apidoc.element.http-errors.402.402)

#### [module http-errors.403](#apidoc.module.http-errors.403)
1.  [function <span class="apidocSignatureSpan">http-errors.403.</span>super_ ()](#apidoc.element.http-errors.403.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>403 (message)](#apidoc.element.http-errors.403.403)

#### [module http-errors.404](#apidoc.module.http-errors.404)
1.  [function <span class="apidocSignatureSpan">http-errors.404.</span>super_ ()](#apidoc.element.http-errors.404.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>404 (message)](#apidoc.element.http-errors.404.404)

#### [module http-errors.405](#apidoc.module.http-errors.405)
1.  [function <span class="apidocSignatureSpan">http-errors.405.</span>super_ ()](#apidoc.element.http-errors.405.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>405 (message)](#apidoc.element.http-errors.405.405)

#### [module http-errors.406](#apidoc.module.http-errors.406)
1.  [function <span class="apidocSignatureSpan">http-errors.406.</span>super_ ()](#apidoc.element.http-errors.406.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>406 (message)](#apidoc.element.http-errors.406.406)

#### [module http-errors.407](#apidoc.module.http-errors.407)
1.  [function <span class="apidocSignatureSpan">http-errors.407.</span>super_ ()](#apidoc.element.http-errors.407.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>407 (message)](#apidoc.element.http-errors.407.407)

#### [module http-errors.408](#apidoc.module.http-errors.408)
1.  [function <span class="apidocSignatureSpan">http-errors.408.</span>super_ ()](#apidoc.element.http-errors.408.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>408 (message)](#apidoc.element.http-errors.408.408)

#### [module http-errors.409](#apidoc.module.http-errors.409)
1.  [function <span class="apidocSignatureSpan">http-errors.409.</span>super_ ()](#apidoc.element.http-errors.409.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>409 (message)](#apidoc.element.http-errors.409.409)

#### [module http-errors.410](#apidoc.module.http-errors.410)
1.  [function <span class="apidocSignatureSpan">http-errors.410.</span>super_ ()](#apidoc.element.http-errors.410.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>410 (message)](#apidoc.element.http-errors.410.410)

#### [module http-errors.411](#apidoc.module.http-errors.411)
1.  [function <span class="apidocSignatureSpan">http-errors.411.</span>super_ ()](#apidoc.element.http-errors.411.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>411 (message)](#apidoc.element.http-errors.411.411)

#### [module http-errors.412](#apidoc.module.http-errors.412)
1.  [function <span class="apidocSignatureSpan">http-errors.412.</span>super_ ()](#apidoc.element.http-errors.412.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>412 (message)](#apidoc.element.http-errors.412.412)

#### [module http-errors.413](#apidoc.module.http-errors.413)
1.  [function <span class="apidocSignatureSpan">http-errors.413.</span>super_ ()](#apidoc.element.http-errors.413.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>413 (message)](#apidoc.element.http-errors.413.413)

#### [module http-errors.414](#apidoc.module.http-errors.414)
1.  [function <span class="apidocSignatureSpan">http-errors.414.</span>super_ ()](#apidoc.element.http-errors.414.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>414 (message)](#apidoc.element.http-errors.414.414)

#### [module http-errors.415](#apidoc.module.http-errors.415)
1.  [function <span class="apidocSignatureSpan">http-errors.415.</span>super_ ()](#apidoc.element.http-errors.415.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>415 (message)](#apidoc.element.http-errors.415.415)

#### [module http-errors.416](#apidoc.module.http-errors.416)
1.  [function <span class="apidocSignatureSpan">http-errors.416.</span>super_ ()](#apidoc.element.http-errors.416.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>416 (message)](#apidoc.element.http-errors.416.416)

#### [module http-errors.417](#apidoc.module.http-errors.417)
1.  [function <span class="apidocSignatureSpan">http-errors.417.</span>super_ ()](#apidoc.element.http-errors.417.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>417 (message)](#apidoc.element.http-errors.417.417)

#### [module http-errors.418](#apidoc.module.http-errors.418)
1.  [function <span class="apidocSignatureSpan">http-errors.418.</span>super_ ()](#apidoc.element.http-errors.418.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>418 (message)](#apidoc.element.http-errors.418.418)

#### [module http-errors.421](#apidoc.module.http-errors.421)
1.  [function <span class="apidocSignatureSpan">http-errors.421.</span>super_ ()](#apidoc.element.http-errors.421.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>421 (message)](#apidoc.element.http-errors.421.421)

#### [module http-errors.422](#apidoc.module.http-errors.422)
1.  [function <span class="apidocSignatureSpan">http-errors.422.</span>super_ ()](#apidoc.element.http-errors.422.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>422 (message)](#apidoc.element.http-errors.422.422)

#### [module http-errors.423](#apidoc.module.http-errors.423)
1.  [function <span class="apidocSignatureSpan">http-errors.423.</span>super_ ()](#apidoc.element.http-errors.423.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>423 (message)](#apidoc.element.http-errors.423.423)

#### [module http-errors.424](#apidoc.module.http-errors.424)
1.  [function <span class="apidocSignatureSpan">http-errors.424.</span>super_ ()](#apidoc.element.http-errors.424.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>424 (message)](#apidoc.element.http-errors.424.424)

#### [module http-errors.425](#apidoc.module.http-errors.425)
1.  [function <span class="apidocSignatureSpan">http-errors.425.</span>super_ ()](#apidoc.element.http-errors.425.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>425 (message)](#apidoc.element.http-errors.425.425)

#### [module http-errors.426](#apidoc.module.http-errors.426)
1.  [function <span class="apidocSignatureSpan">http-errors.426.</span>super_ ()](#apidoc.element.http-errors.426.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>426 (message)](#apidoc.element.http-errors.426.426)

#### [module http-errors.428](#apidoc.module.http-errors.428)
1.  [function <span class="apidocSignatureSpan">http-errors.428.</span>super_ ()](#apidoc.element.http-errors.428.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>428 (message)](#apidoc.element.http-errors.428.428)

#### [module http-errors.429](#apidoc.module.http-errors.429)
1.  [function <span class="apidocSignatureSpan">http-errors.429.</span>super_ ()](#apidoc.element.http-errors.429.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>429 (message)](#apidoc.element.http-errors.429.429)

#### [module http-errors.431](#apidoc.module.http-errors.431)
1.  [function <span class="apidocSignatureSpan">http-errors.431.</span>super_ ()](#apidoc.element.http-errors.431.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>431 (message)](#apidoc.element.http-errors.431.431)

#### [module http-errors.451](#apidoc.module.http-errors.451)
1.  [function <span class="apidocSignatureSpan">http-errors.451.</span>super_ ()](#apidoc.element.http-errors.451.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>451 (message)](#apidoc.element.http-errors.451.451)

#### [module http-errors.500](#apidoc.module.http-errors.500)
1.  [function <span class="apidocSignatureSpan">http-errors.500.</span>super_ ()](#apidoc.element.http-errors.500.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>500 (message)](#apidoc.element.http-errors.500.500)

#### [module http-errors.501](#apidoc.module.http-errors.501)
1.  [function <span class="apidocSignatureSpan">http-errors.501.</span>super_ ()](#apidoc.element.http-errors.501.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>501 (message)](#apidoc.element.http-errors.501.501)

#### [module http-errors.502](#apidoc.module.http-errors.502)
1.  [function <span class="apidocSignatureSpan">http-errors.502.</span>super_ ()](#apidoc.element.http-errors.502.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>502 (message)](#apidoc.element.http-errors.502.502)

#### [module http-errors.503](#apidoc.module.http-errors.503)
1.  [function <span class="apidocSignatureSpan">http-errors.503.</span>super_ ()](#apidoc.element.http-errors.503.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>503 (message)](#apidoc.element.http-errors.503.503)

#### [module http-errors.504](#apidoc.module.http-errors.504)
1.  [function <span class="apidocSignatureSpan">http-errors.504.</span>super_ ()](#apidoc.element.http-errors.504.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>504 (message)](#apidoc.element.http-errors.504.504)

#### [module http-errors.505](#apidoc.module.http-errors.505)
1.  [function <span class="apidocSignatureSpan">http-errors.505.</span>super_ ()](#apidoc.element.http-errors.505.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>505 (message)](#apidoc.element.http-errors.505.505)

#### [module http-errors.506](#apidoc.module.http-errors.506)
1.  [function <span class="apidocSignatureSpan">http-errors.506.</span>super_ ()](#apidoc.element.http-errors.506.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>506 (message)](#apidoc.element.http-errors.506.506)

#### [module http-errors.507](#apidoc.module.http-errors.507)
1.  [function <span class="apidocSignatureSpan">http-errors.507.</span>super_ ()](#apidoc.element.http-errors.507.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>507 (message)](#apidoc.element.http-errors.507.507)

#### [module http-errors.508](#apidoc.module.http-errors.508)
1.  [function <span class="apidocSignatureSpan">http-errors.508.</span>super_ ()](#apidoc.element.http-errors.508.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>508 (message)](#apidoc.element.http-errors.508.508)

#### [module http-errors.509](#apidoc.module.http-errors.509)
1.  [function <span class="apidocSignatureSpan">http-errors.509.</span>super_ ()](#apidoc.element.http-errors.509.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>509 (message)](#apidoc.element.http-errors.509.509)

#### [module http-errors.510](#apidoc.module.http-errors.510)
1.  [function <span class="apidocSignatureSpan">http-errors.510.</span>super_ ()](#apidoc.element.http-errors.510.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>510 (message)](#apidoc.element.http-errors.510.510)

#### [module http-errors.511](#apidoc.module.http-errors.511)
1.  [function <span class="apidocSignatureSpan">http-errors.511.</span>super_ ()](#apidoc.element.http-errors.511.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>511 (message)](#apidoc.element.http-errors.511.511)

#### [module http-errors.HttpError](#apidoc.module.http-errors.HttpError)
1.  [function <span class="apidocSignatureSpan">http-errors.</span>HttpError ()](#apidoc.element.http-errors.HttpError.HttpError)
1.  [function <span class="apidocSignatureSpan">http-errors.HttpError.</span>super_ ()](#apidoc.element.http-errors.HttpError.super_)

#### [module http-errors.HttpError.super_](#apidoc.module.http-errors.HttpError.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.HttpError.</span>super_ ()](#apidoc.element.http-errors.HttpError.super_.super_)
1.  [function <span class="apidocSignatureSpan">http-errors.HttpError.super_.</span>captureStackTrace ()](#apidoc.element.http-errors.HttpError.super_.captureStackTrace)
1.  number <span class="apidocSignatureSpan">http-errors.HttpError.super_.</span>stackTraceLimit



# <a name="apidoc.module.http-errors"></a>[module http-errors](#apidoc.module.http-errors)

#### <a name="apidoc.element.http-errors.400"></a>[function <span class="apidocSignatureSpan">http-errors.</span>400 (message)](#apidoc.element.http-errors.400)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.401"></a>[function <span class="apidocSignatureSpan">http-errors.</span>401 (message)](#apidoc.element.http-errors.401)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.402"></a>[function <span class="apidocSignatureSpan">http-errors.</span>402 (message)](#apidoc.element.http-errors.402)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.403"></a>[function <span class="apidocSignatureSpan">http-errors.</span>403 (message)](#apidoc.element.http-errors.403)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.404"></a>[function <span class="apidocSignatureSpan">http-errors.</span>404 (message)](#apidoc.element.http-errors.404)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.405"></a>[function <span class="apidocSignatureSpan">http-errors.</span>405 (message)](#apidoc.element.http-errors.405)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.406"></a>[function <span class="apidocSignatureSpan">http-errors.</span>406 (message)](#apidoc.element.http-errors.406)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.407"></a>[function <span class="apidocSignatureSpan">http-errors.</span>407 (message)](#apidoc.element.http-errors.407)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.408"></a>[function <span class="apidocSignatureSpan">http-errors.</span>408 (message)](#apidoc.element.http-errors.408)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.409"></a>[function <span class="apidocSignatureSpan">http-errors.</span>409 (message)](#apidoc.element.http-errors.409)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.410"></a>[function <span class="apidocSignatureSpan">http-errors.</span>410 (message)](#apidoc.element.http-errors.410)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.411"></a>[function <span class="apidocSignatureSpan">http-errors.</span>411 (message)](#apidoc.element.http-errors.411)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.412"></a>[function <span class="apidocSignatureSpan">http-errors.</span>412 (message)](#apidoc.element.http-errors.412)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.413"></a>[function <span class="apidocSignatureSpan">http-errors.</span>413 (message)](#apidoc.element.http-errors.413)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.414"></a>[function <span class="apidocSignatureSpan">http-errors.</span>414 (message)](#apidoc.element.http-errors.414)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.415"></a>[function <span class="apidocSignatureSpan">http-errors.</span>415 (message)](#apidoc.element.http-errors.415)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.416"></a>[function <span class="apidocSignatureSpan">http-errors.</span>416 (message)](#apidoc.element.http-errors.416)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.417"></a>[function <span class="apidocSignatureSpan">http-errors.</span>417 (message)](#apidoc.element.http-errors.417)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.418"></a>[function <span class="apidocSignatureSpan">http-errors.</span>418 (message)](#apidoc.element.http-errors.418)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.421"></a>[function <span class="apidocSignatureSpan">http-errors.</span>421 (message)](#apidoc.element.http-errors.421)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.422"></a>[function <span class="apidocSignatureSpan">http-errors.</span>422 (message)](#apidoc.element.http-errors.422)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.423"></a>[function <span class="apidocSignatureSpan">http-errors.</span>423 (message)](#apidoc.element.http-errors.423)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.424"></a>[function <span class="apidocSignatureSpan">http-errors.</span>424 (message)](#apidoc.element.http-errors.424)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.425"></a>[function <span class="apidocSignatureSpan">http-errors.</span>425 (message)](#apidoc.element.http-errors.425)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.426"></a>[function <span class="apidocSignatureSpan">http-errors.</span>426 (message)](#apidoc.element.http-errors.426)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.428"></a>[function <span class="apidocSignatureSpan">http-errors.</span>428 (message)](#apidoc.element.http-errors.428)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.429"></a>[function <span class="apidocSignatureSpan">http-errors.</span>429 (message)](#apidoc.element.http-errors.429)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.431"></a>[function <span class="apidocSignatureSpan">http-errors.</span>431 (message)](#apidoc.element.http-errors.431)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.451"></a>[function <span class="apidocSignatureSpan">http-errors.</span>451 (message)](#apidoc.element.http-errors.451)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.500"></a>[function <span class="apidocSignatureSpan">http-errors.</span>500 (message)](#apidoc.element.http-errors.500)
- description and source-code
```javascript
function ServerError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ServerError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ServerError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.501"></a>[function <span class="apidocSignatureSpan">http-errors.</span>501 (message)](#apidoc.element.http-errors.501)
- description and source-code
```javascript
function ServerError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ServerError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ServerError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.502"></a>[function <span class="apidocSignatureSpan">http-errors.</span>502 (message)](#apidoc.element.http-errors.502)
- description and source-code
```javascript
function ServerError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ServerError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ServerError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.503"></a>[function <span class="apidocSignatureSpan">http-errors.</span>503 (message)](#apidoc.element.http-errors.503)
- description and source-code
```javascript
function ServerError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ServerError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ServerError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.504"></a>[function <span class="apidocSignatureSpan">http-errors.</span>504 (message)](#apidoc.element.http-errors.504)
- description and source-code
```javascript
function ServerError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ServerError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ServerError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.505"></a>[function <span class="apidocSignatureSpan">http-errors.</span>505 (message)](#apidoc.element.http-errors.505)
- description and source-code
```javascript
function ServerError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ServerError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ServerError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.506"></a>[function <span class="apidocSignatureSpan">http-errors.</span>506 (message)](#apidoc.element.http-errors.506)
- description and source-code
```javascript
function ServerError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ServerError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ServerError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.507"></a>[function <span class="apidocSignatureSpan">http-errors.</span>507 (message)](#apidoc.element.http-errors.507)
- description and source-code
```javascript
function ServerError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ServerError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ServerError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.508"></a>[function <span class="apidocSignatureSpan">http-errors.</span>508 (message)](#apidoc.element.http-errors.508)
- description and source-code
```javascript
function ServerError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ServerError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ServerError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.509"></a>[function <span class="apidocSignatureSpan">http-errors.</span>509 (message)](#apidoc.element.http-errors.509)
- description and source-code
```javascript
function ServerError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ServerError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ServerError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.510"></a>[function <span class="apidocSignatureSpan">http-errors.</span>510 (message)](#apidoc.element.http-errors.510)
- description and source-code
```javascript
function ServerError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ServerError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ServerError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.511"></a>[function <span class="apidocSignatureSpan">http-errors.</span>511 (message)](#apidoc.element.http-errors.511)
- description and source-code
```javascript
function ServerError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ServerError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ServerError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.BadGateway"></a>[function <span class="apidocSignatureSpan">http-errors.</span>BadGateway (message)](#apidoc.element.http-errors.BadGateway)
- description and source-code
```javascript
function ServerError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ServerError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ServerError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.BadRequest"></a>[function <span class="apidocSignatureSpan">http-errors.</span>BadRequest (message)](#apidoc.element.http-errors.BadRequest)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.BandwidthLimitExceeded"></a>[function <span class="apidocSignatureSpan">http-errors.</span>BandwidthLimitExceeded (message)](#apidoc.element.http-errors.BandwidthLimitExceeded)
- description and source-code
```javascript
function ServerError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ServerError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ServerError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.Conflict"></a>[function <span class="apidocSignatureSpan">http-errors.</span>Conflict (message)](#apidoc.element.http-errors.Conflict)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.ExpectationFailed"></a>[function <span class="apidocSignatureSpan">http-errors.</span>ExpectationFailed (message)](#apidoc.element.http-errors.ExpectationFailed)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.FailedDependency"></a>[function <span class="apidocSignatureSpan">http-errors.</span>FailedDependency (message)](#apidoc.element.http-errors.FailedDependency)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.Forbidden"></a>[function <span class="apidocSignatureSpan">http-errors.</span>Forbidden (message)](#apidoc.element.http-errors.Forbidden)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.GatewayTimeout"></a>[function <span class="apidocSignatureSpan">http-errors.</span>GatewayTimeout (message)](#apidoc.element.http-errors.GatewayTimeout)
- description and source-code
```javascript
function ServerError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ServerError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ServerError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.Gone"></a>[function <span class="apidocSignatureSpan">http-errors.</span>Gone (message)](#apidoc.element.http-errors.Gone)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.HTTPVersionNotSupported"></a>[function <span class="apidocSignatureSpan">http-errors.</span>HTTPVersionNotSupported (message)](#apidoc.element.http-errors.HTTPVersionNotSupported)
- description and source-code
```javascript
function ServerError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ServerError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ServerError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.HttpError"></a>[function <span class="apidocSignatureSpan">http-errors.</span>HttpError ()](#apidoc.element.http-errors.HttpError)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.HttpError.super_"></a>[function <span class="apidocSignatureSpan">http-errors.</span>HttpError.super_ ()](#apidoc.element.http-errors.HttpError.super_)
- description and source-code
```javascript
function Error() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.ImATeapot"></a>[function <span class="apidocSignatureSpan">http-errors.</span>ImATeapot (message)](#apidoc.element.http-errors.ImATeapot)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.InsufficientStorage"></a>[function <span class="apidocSignatureSpan">http-errors.</span>InsufficientStorage (message)](#apidoc.element.http-errors.InsufficientStorage)
- description and source-code
```javascript
function ServerError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ServerError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ServerError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.InternalServerError"></a>[function <span class="apidocSignatureSpan">http-errors.</span>InternalServerError (message)](#apidoc.element.http-errors.InternalServerError)
- description and source-code
```javascript
function ServerError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ServerError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ServerError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.LengthRequired"></a>[function <span class="apidocSignatureSpan">http-errors.</span>LengthRequired (message)](#apidoc.element.http-errors.LengthRequired)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.Locked"></a>[function <span class="apidocSignatureSpan">http-errors.</span>Locked (message)](#apidoc.element.http-errors.Locked)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.LoopDetected"></a>[function <span class="apidocSignatureSpan">http-errors.</span>LoopDetected (message)](#apidoc.element.http-errors.LoopDetected)
- description and source-code
```javascript
function ServerError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ServerError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ServerError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.MethodNotAllowed"></a>[function <span class="apidocSignatureSpan">http-errors.</span>MethodNotAllowed (message)](#apidoc.element.http-errors.MethodNotAllowed)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.MisdirectedRequest"></a>[function <span class="apidocSignatureSpan">http-errors.</span>MisdirectedRequest (message)](#apidoc.element.http-errors.MisdirectedRequest)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.NetworkAuthenticationRequired"></a>[function <span class="apidocSignatureSpan">http-errors.</span>NetworkAuthenticationRequired (message)](#apidoc.element.http-errors.NetworkAuthenticationRequired)
- description and source-code
```javascript
function ServerError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ServerError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ServerError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.NotAcceptable"></a>[function <span class="apidocSignatureSpan">http-errors.</span>NotAcceptable (message)](#apidoc.element.http-errors.NotAcceptable)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.NotExtended"></a>[function <span class="apidocSignatureSpan">http-errors.</span>NotExtended (message)](#apidoc.element.http-errors.NotExtended)
- description and source-code
```javascript
function ServerError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ServerError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ServerError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.NotFound"></a>[function <span class="apidocSignatureSpan">http-errors.</span>NotFound (message)](#apidoc.element.http-errors.NotFound)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
...
- 'properties' - custom properties to attach to the object

### new createError\[code || name\](\[msg]\))

<!-- eslint-disable no-undef, no-unused-vars -->

'''js
var err = new createError.NotFound()
'''

- 'code' - the status code as a number
- 'name' - the name of the error as a "bumpy case", i.e. 'NotFound' or 'InternalServerError'.

#### List of all constructors
...
```

#### <a name="apidoc.element.http-errors.NotImplemented"></a>[function <span class="apidocSignatureSpan">http-errors.</span>NotImplemented (message)](#apidoc.element.http-errors.NotImplemented)
- description and source-code
```javascript
function ServerError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ServerError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ServerError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.PayloadTooLarge"></a>[function <span class="apidocSignatureSpan">http-errors.</span>PayloadTooLarge (message)](#apidoc.element.http-errors.PayloadTooLarge)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.PaymentRequired"></a>[function <span class="apidocSignatureSpan">http-errors.</span>PaymentRequired (message)](#apidoc.element.http-errors.PaymentRequired)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.PreconditionFailed"></a>[function <span class="apidocSignatureSpan">http-errors.</span>PreconditionFailed (message)](#apidoc.element.http-errors.PreconditionFailed)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.PreconditionRequired"></a>[function <span class="apidocSignatureSpan">http-errors.</span>PreconditionRequired (message)](#apidoc.element.http-errors.PreconditionRequired)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.ProxyAuthenticationRequired"></a>[function <span class="apidocSignatureSpan">http-errors.</span>ProxyAuthenticationRequired (message)](#apidoc.element.http-errors.ProxyAuthenticationRequired)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.RangeNotSatisfiable"></a>[function <span class="apidocSignatureSpan">http-errors.</span>RangeNotSatisfiable (message)](#apidoc.element.http-errors.RangeNotSatisfiable)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.RequestHeaderFieldsTooLarge"></a>[function <span class="apidocSignatureSpan">http-errors.</span>RequestHeaderFieldsTooLarge (message)](#apidoc.element.http-errors.RequestHeaderFieldsTooLarge)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.RequestTimeout"></a>[function <span class="apidocSignatureSpan">http-errors.</span>RequestTimeout (message)](#apidoc.element.http-errors.RequestTimeout)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.ServiceUnavailable"></a>[function <span class="apidocSignatureSpan">http-errors.</span>ServiceUnavailable (message)](#apidoc.element.http-errors.ServiceUnavailable)
- description and source-code
```javascript
function ServerError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ServerError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ServerError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.TooManyRequests"></a>[function <span class="apidocSignatureSpan">http-errors.</span>TooManyRequests (message)](#apidoc.element.http-errors.TooManyRequests)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.URITooLong"></a>[function <span class="apidocSignatureSpan">http-errors.</span>URITooLong (message)](#apidoc.element.http-errors.URITooLong)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.Unauthorized"></a>[function <span class="apidocSignatureSpan">http-errors.</span>Unauthorized (message)](#apidoc.element.http-errors.Unauthorized)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.UnavailableForLegalReasons"></a>[function <span class="apidocSignatureSpan">http-errors.</span>UnavailableForLegalReasons (message)](#apidoc.element.http-errors.UnavailableForLegalReasons)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.UnorderedCollection"></a>[function <span class="apidocSignatureSpan">http-errors.</span>UnorderedCollection (message)](#apidoc.element.http-errors.UnorderedCollection)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.UnprocessableEntity"></a>[function <span class="apidocSignatureSpan">http-errors.</span>UnprocessableEntity (message)](#apidoc.element.http-errors.UnprocessableEntity)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.UnsupportedMediaType"></a>[function <span class="apidocSignatureSpan">http-errors.</span>UnsupportedMediaType (message)](#apidoc.element.http-errors.UnsupportedMediaType)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.UpgradeRequired"></a>[function <span class="apidocSignatureSpan">http-errors.</span>UpgradeRequired (message)](#apidoc.element.http-errors.UpgradeRequired)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.VariantAlsoNegotiates"></a>[function <span class="apidocSignatureSpan">http-errors.</span>VariantAlsoNegotiates (message)](#apidoc.element.http-errors.VariantAlsoNegotiates)
- description and source-code
```javascript
function ServerError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ServerError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ServerError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.400"></a>[module http-errors.400](#apidoc.module.http-errors.400)

#### <a name="apidoc.element.http-errors.400.super_"></a>[function <span class="apidocSignatureSpan">http-errors.400.</span>super_ ()](#apidoc.element.http-errors.400.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.400.400"></a>[function <span class="apidocSignatureSpan">http-errors.</span>400 (message)](#apidoc.element.http-errors.400.400)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.401"></a>[module http-errors.401](#apidoc.module.http-errors.401)

#### <a name="apidoc.element.http-errors.401.super_"></a>[function <span class="apidocSignatureSpan">http-errors.401.</span>super_ ()](#apidoc.element.http-errors.401.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.401.401"></a>[function <span class="apidocSignatureSpan">http-errors.</span>401 (message)](#apidoc.element.http-errors.401.401)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.402"></a>[module http-errors.402](#apidoc.module.http-errors.402)

#### <a name="apidoc.element.http-errors.402.super_"></a>[function <span class="apidocSignatureSpan">http-errors.402.</span>super_ ()](#apidoc.element.http-errors.402.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.402.402"></a>[function <span class="apidocSignatureSpan">http-errors.</span>402 (message)](#apidoc.element.http-errors.402.402)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.403"></a>[module http-errors.403](#apidoc.module.http-errors.403)

#### <a name="apidoc.element.http-errors.403.super_"></a>[function <span class="apidocSignatureSpan">http-errors.403.</span>super_ ()](#apidoc.element.http-errors.403.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.403.403"></a>[function <span class="apidocSignatureSpan">http-errors.</span>403 (message)](#apidoc.element.http-errors.403.403)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.404"></a>[module http-errors.404](#apidoc.module.http-errors.404)

#### <a name="apidoc.element.http-errors.404.super_"></a>[function <span class="apidocSignatureSpan">http-errors.404.</span>super_ ()](#apidoc.element.http-errors.404.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.404.404"></a>[function <span class="apidocSignatureSpan">http-errors.</span>404 (message)](#apidoc.element.http-errors.404.404)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.405"></a>[module http-errors.405](#apidoc.module.http-errors.405)

#### <a name="apidoc.element.http-errors.405.super_"></a>[function <span class="apidocSignatureSpan">http-errors.405.</span>super_ ()](#apidoc.element.http-errors.405.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.405.405"></a>[function <span class="apidocSignatureSpan">http-errors.</span>405 (message)](#apidoc.element.http-errors.405.405)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.406"></a>[module http-errors.406](#apidoc.module.http-errors.406)

#### <a name="apidoc.element.http-errors.406.super_"></a>[function <span class="apidocSignatureSpan">http-errors.406.</span>super_ ()](#apidoc.element.http-errors.406.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.406.406"></a>[function <span class="apidocSignatureSpan">http-errors.</span>406 (message)](#apidoc.element.http-errors.406.406)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.407"></a>[module http-errors.407](#apidoc.module.http-errors.407)

#### <a name="apidoc.element.http-errors.407.super_"></a>[function <span class="apidocSignatureSpan">http-errors.407.</span>super_ ()](#apidoc.element.http-errors.407.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.407.407"></a>[function <span class="apidocSignatureSpan">http-errors.</span>407 (message)](#apidoc.element.http-errors.407.407)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.408"></a>[module http-errors.408](#apidoc.module.http-errors.408)

#### <a name="apidoc.element.http-errors.408.super_"></a>[function <span class="apidocSignatureSpan">http-errors.408.</span>super_ ()](#apidoc.element.http-errors.408.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.408.408"></a>[function <span class="apidocSignatureSpan">http-errors.</span>408 (message)](#apidoc.element.http-errors.408.408)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.409"></a>[module http-errors.409](#apidoc.module.http-errors.409)

#### <a name="apidoc.element.http-errors.409.super_"></a>[function <span class="apidocSignatureSpan">http-errors.409.</span>super_ ()](#apidoc.element.http-errors.409.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.409.409"></a>[function <span class="apidocSignatureSpan">http-errors.</span>409 (message)](#apidoc.element.http-errors.409.409)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.410"></a>[module http-errors.410](#apidoc.module.http-errors.410)

#### <a name="apidoc.element.http-errors.410.super_"></a>[function <span class="apidocSignatureSpan">http-errors.410.</span>super_ ()](#apidoc.element.http-errors.410.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.410.410"></a>[function <span class="apidocSignatureSpan">http-errors.</span>410 (message)](#apidoc.element.http-errors.410.410)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.411"></a>[module http-errors.411](#apidoc.module.http-errors.411)

#### <a name="apidoc.element.http-errors.411.super_"></a>[function <span class="apidocSignatureSpan">http-errors.411.</span>super_ ()](#apidoc.element.http-errors.411.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.411.411"></a>[function <span class="apidocSignatureSpan">http-errors.</span>411 (message)](#apidoc.element.http-errors.411.411)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.412"></a>[module http-errors.412](#apidoc.module.http-errors.412)

#### <a name="apidoc.element.http-errors.412.super_"></a>[function <span class="apidocSignatureSpan">http-errors.412.</span>super_ ()](#apidoc.element.http-errors.412.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.412.412"></a>[function <span class="apidocSignatureSpan">http-errors.</span>412 (message)](#apidoc.element.http-errors.412.412)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.413"></a>[module http-errors.413](#apidoc.module.http-errors.413)

#### <a name="apidoc.element.http-errors.413.super_"></a>[function <span class="apidocSignatureSpan">http-errors.413.</span>super_ ()](#apidoc.element.http-errors.413.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.413.413"></a>[function <span class="apidocSignatureSpan">http-errors.</span>413 (message)](#apidoc.element.http-errors.413.413)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.414"></a>[module http-errors.414](#apidoc.module.http-errors.414)

#### <a name="apidoc.element.http-errors.414.super_"></a>[function <span class="apidocSignatureSpan">http-errors.414.</span>super_ ()](#apidoc.element.http-errors.414.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.414.414"></a>[function <span class="apidocSignatureSpan">http-errors.</span>414 (message)](#apidoc.element.http-errors.414.414)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.415"></a>[module http-errors.415](#apidoc.module.http-errors.415)

#### <a name="apidoc.element.http-errors.415.super_"></a>[function <span class="apidocSignatureSpan">http-errors.415.</span>super_ ()](#apidoc.element.http-errors.415.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.415.415"></a>[function <span class="apidocSignatureSpan">http-errors.</span>415 (message)](#apidoc.element.http-errors.415.415)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.416"></a>[module http-errors.416](#apidoc.module.http-errors.416)

#### <a name="apidoc.element.http-errors.416.super_"></a>[function <span class="apidocSignatureSpan">http-errors.416.</span>super_ ()](#apidoc.element.http-errors.416.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.416.416"></a>[function <span class="apidocSignatureSpan">http-errors.</span>416 (message)](#apidoc.element.http-errors.416.416)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.417"></a>[module http-errors.417](#apidoc.module.http-errors.417)

#### <a name="apidoc.element.http-errors.417.super_"></a>[function <span class="apidocSignatureSpan">http-errors.417.</span>super_ ()](#apidoc.element.http-errors.417.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.417.417"></a>[function <span class="apidocSignatureSpan">http-errors.</span>417 (message)](#apidoc.element.http-errors.417.417)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.418"></a>[module http-errors.418](#apidoc.module.http-errors.418)

#### <a name="apidoc.element.http-errors.418.super_"></a>[function <span class="apidocSignatureSpan">http-errors.418.</span>super_ ()](#apidoc.element.http-errors.418.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.418.418"></a>[function <span class="apidocSignatureSpan">http-errors.</span>418 (message)](#apidoc.element.http-errors.418.418)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.421"></a>[module http-errors.421](#apidoc.module.http-errors.421)

#### <a name="apidoc.element.http-errors.421.super_"></a>[function <span class="apidocSignatureSpan">http-errors.421.</span>super_ ()](#apidoc.element.http-errors.421.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.421.421"></a>[function <span class="apidocSignatureSpan">http-errors.</span>421 (message)](#apidoc.element.http-errors.421.421)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.422"></a>[module http-errors.422](#apidoc.module.http-errors.422)

#### <a name="apidoc.element.http-errors.422.super_"></a>[function <span class="apidocSignatureSpan">http-errors.422.</span>super_ ()](#apidoc.element.http-errors.422.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.422.422"></a>[function <span class="apidocSignatureSpan">http-errors.</span>422 (message)](#apidoc.element.http-errors.422.422)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.423"></a>[module http-errors.423](#apidoc.module.http-errors.423)

#### <a name="apidoc.element.http-errors.423.super_"></a>[function <span class="apidocSignatureSpan">http-errors.423.</span>super_ ()](#apidoc.element.http-errors.423.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.423.423"></a>[function <span class="apidocSignatureSpan">http-errors.</span>423 (message)](#apidoc.element.http-errors.423.423)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.424"></a>[module http-errors.424](#apidoc.module.http-errors.424)

#### <a name="apidoc.element.http-errors.424.super_"></a>[function <span class="apidocSignatureSpan">http-errors.424.</span>super_ ()](#apidoc.element.http-errors.424.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.424.424"></a>[function <span class="apidocSignatureSpan">http-errors.</span>424 (message)](#apidoc.element.http-errors.424.424)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.425"></a>[module http-errors.425](#apidoc.module.http-errors.425)

#### <a name="apidoc.element.http-errors.425.super_"></a>[function <span class="apidocSignatureSpan">http-errors.425.</span>super_ ()](#apidoc.element.http-errors.425.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.425.425"></a>[function <span class="apidocSignatureSpan">http-errors.</span>425 (message)](#apidoc.element.http-errors.425.425)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.426"></a>[module http-errors.426](#apidoc.module.http-errors.426)

#### <a name="apidoc.element.http-errors.426.super_"></a>[function <span class="apidocSignatureSpan">http-errors.426.</span>super_ ()](#apidoc.element.http-errors.426.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.426.426"></a>[function <span class="apidocSignatureSpan">http-errors.</span>426 (message)](#apidoc.element.http-errors.426.426)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.428"></a>[module http-errors.428](#apidoc.module.http-errors.428)

#### <a name="apidoc.element.http-errors.428.super_"></a>[function <span class="apidocSignatureSpan">http-errors.428.</span>super_ ()](#apidoc.element.http-errors.428.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.428.428"></a>[function <span class="apidocSignatureSpan">http-errors.</span>428 (message)](#apidoc.element.http-errors.428.428)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.429"></a>[module http-errors.429](#apidoc.module.http-errors.429)

#### <a name="apidoc.element.http-errors.429.super_"></a>[function <span class="apidocSignatureSpan">http-errors.429.</span>super_ ()](#apidoc.element.http-errors.429.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.429.429"></a>[function <span class="apidocSignatureSpan">http-errors.</span>429 (message)](#apidoc.element.http-errors.429.429)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.431"></a>[module http-errors.431](#apidoc.module.http-errors.431)

#### <a name="apidoc.element.http-errors.431.super_"></a>[function <span class="apidocSignatureSpan">http-errors.431.</span>super_ ()](#apidoc.element.http-errors.431.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.431.431"></a>[function <span class="apidocSignatureSpan">http-errors.</span>431 (message)](#apidoc.element.http-errors.431.431)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.451"></a>[module http-errors.451](#apidoc.module.http-errors.451)

#### <a name="apidoc.element.http-errors.451.super_"></a>[function <span class="apidocSignatureSpan">http-errors.451.</span>super_ ()](#apidoc.element.http-errors.451.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.451.451"></a>[function <span class="apidocSignatureSpan">http-errors.</span>451 (message)](#apidoc.element.http-errors.451.451)
- description and source-code
```javascript
function ClientError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ClientError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ClientError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.500"></a>[module http-errors.500](#apidoc.module.http-errors.500)

#### <a name="apidoc.element.http-errors.500.super_"></a>[function <span class="apidocSignatureSpan">http-errors.500.</span>super_ ()](#apidoc.element.http-errors.500.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.500.500"></a>[function <span class="apidocSignatureSpan">http-errors.</span>500 (message)](#apidoc.element.http-errors.500.500)
- description and source-code
```javascript
function ServerError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ServerError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ServerError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.501"></a>[module http-errors.501](#apidoc.module.http-errors.501)

#### <a name="apidoc.element.http-errors.501.super_"></a>[function <span class="apidocSignatureSpan">http-errors.501.</span>super_ ()](#apidoc.element.http-errors.501.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.501.501"></a>[function <span class="apidocSignatureSpan">http-errors.</span>501 (message)](#apidoc.element.http-errors.501.501)
- description and source-code
```javascript
function ServerError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ServerError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ServerError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.502"></a>[module http-errors.502](#apidoc.module.http-errors.502)

#### <a name="apidoc.element.http-errors.502.super_"></a>[function <span class="apidocSignatureSpan">http-errors.502.</span>super_ ()](#apidoc.element.http-errors.502.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.502.502"></a>[function <span class="apidocSignatureSpan">http-errors.</span>502 (message)](#apidoc.element.http-errors.502.502)
- description and source-code
```javascript
function ServerError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ServerError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ServerError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.503"></a>[module http-errors.503](#apidoc.module.http-errors.503)

#### <a name="apidoc.element.http-errors.503.super_"></a>[function <span class="apidocSignatureSpan">http-errors.503.</span>super_ ()](#apidoc.element.http-errors.503.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.503.503"></a>[function <span class="apidocSignatureSpan">http-errors.</span>503 (message)](#apidoc.element.http-errors.503.503)
- description and source-code
```javascript
function ServerError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ServerError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ServerError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.504"></a>[module http-errors.504](#apidoc.module.http-errors.504)

#### <a name="apidoc.element.http-errors.504.super_"></a>[function <span class="apidocSignatureSpan">http-errors.504.</span>super_ ()](#apidoc.element.http-errors.504.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.504.504"></a>[function <span class="apidocSignatureSpan">http-errors.</span>504 (message)](#apidoc.element.http-errors.504.504)
- description and source-code
```javascript
function ServerError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ServerError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ServerError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.505"></a>[module http-errors.505](#apidoc.module.http-errors.505)

#### <a name="apidoc.element.http-errors.505.super_"></a>[function <span class="apidocSignatureSpan">http-errors.505.</span>super_ ()](#apidoc.element.http-errors.505.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.505.505"></a>[function <span class="apidocSignatureSpan">http-errors.</span>505 (message)](#apidoc.element.http-errors.505.505)
- description and source-code
```javascript
function ServerError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ServerError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ServerError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.506"></a>[module http-errors.506](#apidoc.module.http-errors.506)

#### <a name="apidoc.element.http-errors.506.super_"></a>[function <span class="apidocSignatureSpan">http-errors.506.</span>super_ ()](#apidoc.element.http-errors.506.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.506.506"></a>[function <span class="apidocSignatureSpan">http-errors.</span>506 (message)](#apidoc.element.http-errors.506.506)
- description and source-code
```javascript
function ServerError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ServerError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ServerError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.507"></a>[module http-errors.507](#apidoc.module.http-errors.507)

#### <a name="apidoc.element.http-errors.507.super_"></a>[function <span class="apidocSignatureSpan">http-errors.507.</span>super_ ()](#apidoc.element.http-errors.507.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.507.507"></a>[function <span class="apidocSignatureSpan">http-errors.</span>507 (message)](#apidoc.element.http-errors.507.507)
- description and source-code
```javascript
function ServerError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ServerError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ServerError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.508"></a>[module http-errors.508](#apidoc.module.http-errors.508)

#### <a name="apidoc.element.http-errors.508.super_"></a>[function <span class="apidocSignatureSpan">http-errors.508.</span>super_ ()](#apidoc.element.http-errors.508.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.508.508"></a>[function <span class="apidocSignatureSpan">http-errors.</span>508 (message)](#apidoc.element.http-errors.508.508)
- description and source-code
```javascript
function ServerError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ServerError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ServerError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.509"></a>[module http-errors.509](#apidoc.module.http-errors.509)

#### <a name="apidoc.element.http-errors.509.super_"></a>[function <span class="apidocSignatureSpan">http-errors.509.</span>super_ ()](#apidoc.element.http-errors.509.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.509.509"></a>[function <span class="apidocSignatureSpan">http-errors.</span>509 (message)](#apidoc.element.http-errors.509.509)
- description and source-code
```javascript
function ServerError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ServerError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ServerError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.510"></a>[module http-errors.510](#apidoc.module.http-errors.510)

#### <a name="apidoc.element.http-errors.510.super_"></a>[function <span class="apidocSignatureSpan">http-errors.510.</span>super_ ()](#apidoc.element.http-errors.510.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.510.510"></a>[function <span class="apidocSignatureSpan">http-errors.</span>510 (message)](#apidoc.element.http-errors.510.510)
- description and source-code
```javascript
function ServerError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ServerError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ServerError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.511"></a>[module http-errors.511](#apidoc.module.http-errors.511)

#### <a name="apidoc.element.http-errors.511.super_"></a>[function <span class="apidocSignatureSpan">http-errors.511.</span>super_ ()](#apidoc.element.http-errors.511.super_)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.511.511"></a>[function <span class="apidocSignatureSpan">http-errors.</span>511 (message)](#apidoc.element.http-errors.511.511)
- description and source-code
```javascript
function ServerError(message) {
  // create the error object
  var msg = message != null ? message : statuses[code]
  var err = new Error(msg)

  // capture a stack trace to the construction point
  Error.captureStackTrace(err, ServerError)

  // adjust the [[Prototype]]
  setPrototypeOf(err, ServerError.prototype)

  // redefine the error message
  Object.defineProperty(err, 'message', {
    enumerable: true,
    configurable: true,
    value: msg,
    writable: true
  })

  // redefine the error name
  Object.defineProperty(err, 'name', {
    enumerable: false,
    configurable: true,
    value: className,
    writable: true
  })

  return err
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.HttpError"></a>[module http-errors.HttpError](#apidoc.module.http-errors.HttpError)

#### <a name="apidoc.element.http-errors.HttpError.HttpError"></a>[function <span class="apidocSignatureSpan">http-errors.</span>HttpError ()](#apidoc.element.http-errors.HttpError.HttpError)
- description and source-code
```javascript
function HttpError() {
  throw new TypeError('cannot construct abstract class')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.HttpError.super_"></a>[function <span class="apidocSignatureSpan">http-errors.HttpError.</span>super_ ()](#apidoc.element.http-errors.HttpError.super_)
- description and source-code
```javascript
function Error() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.http-errors.HttpError.super_"></a>[module http-errors.HttpError.super_](#apidoc.module.http-errors.HttpError.super_)

#### <a name="apidoc.element.http-errors.HttpError.super_.super_"></a>[function <span class="apidocSignatureSpan">http-errors.HttpError.</span>super_ ()](#apidoc.element.http-errors.HttpError.super_.super_)
- description and source-code
```javascript
function Error() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.http-errors.HttpError.super_.captureStackTrace"></a>[function <span class="apidocSignatureSpan">http-errors.HttpError.super_.</span>captureStackTrace ()](#apidoc.element.http-errors.HttpError.super_.captureStackTrace)
- description and source-code
```javascript
function captureStackTrace() { [native code] }
```
- example usage
```shell
...
var HttpError = createError[status] || createError[codeClass(status)]

if (!err) {
  // create error
  err = HttpError
    ? new HttpError(msg)
    : new Error(msg || statuses[status])
  Error.captureStackTrace(err, createError)
}

if (!HttpError || !(err instanceof HttpError) || err.status !== status) {
  // add properties to generic error
  err.expose = status < 500
  err.status = err.statusCode = status
}
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
