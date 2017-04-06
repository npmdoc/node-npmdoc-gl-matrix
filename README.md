# api documentation for  [gl-matrix (v2.3.2)](http://glmatrix.net)  [![npm package](https://img.shields.io/npm/v/npmdoc-gl-matrix.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gl-matrix) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gl-matrix.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gl-matrix)
#### Javascript Matrix and Vector library for High Performance WebGL apps

[![NPM](https://nodei.co/npm/gl-matrix.png?downloads=true)](https://www.npmjs.com/package/gl-matrix)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gl-matrix/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-gl-matrix_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gl-matrix/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gl-matrix/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gl-matrix/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/toji/gl-matrix/issues"
    },
    "contributors": [
        {
            "name": "Brandon Jones",
            "email": "tojiro@gmail.com"
        },
        {
            "name": "Colin MacKenzie IV",
            "email": "sinisterchipmunk@gmail.com"
        }
    ],
    "dependencies": {},
    "description": "Javascript Matrix and Vector library for High Performance WebGL apps",
    "devDependencies": {
        "jasmine-node": "1.2.2",
        "node-libs-browser": "^0.5.2",
        "simd": "2.0.0",
        "webpack": "^1.9.10"
    },
    "directories": {},
    "dist": {
        "shasum": "aac808c74af7d5db05fe04cb60ca1a0fcb174d74",
        "tarball": "https://registry.npmjs.org/gl-matrix/-/gl-matrix-2.3.2.tgz"
    },
    "gitHead": "6723211d7adcde84f4b3f5cfc9c3f75eb8acaccb",
    "homepage": "http://glmatrix.net",
    "license": "MIT",
    "main": "src/gl-matrix.js",
    "maintainers": [
        {
            "name": "toji",
            "email": "tojiro@gmail.com"
        },
        {
            "name": "hughsk",
            "email": "hughskennedy@gmail.com"
        }
    ],
    "name": "gl-matrix",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/toji/gl-matrix.git"
    },
    "scripts": {
        "test": "jasmine-node spec"
    },
    "version": "2.3.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module gl-matrix](#apidoc.module.gl-matrix)
1.  object <span class="apidocSignatureSpan">gl-matrix.</span>glMatrix
1.  object <span class="apidocSignatureSpan">gl-matrix.</span>mat2
1.  object <span class="apidocSignatureSpan">gl-matrix.</span>mat2d
1.  object <span class="apidocSignatureSpan">gl-matrix.</span>mat3
1.  object <span class="apidocSignatureSpan">gl-matrix.</span>mat4
1.  object <span class="apidocSignatureSpan">gl-matrix.</span>mat4.SIMD
1.  object <span class="apidocSignatureSpan">gl-matrix.</span>mat4.scalar
1.  object <span class="apidocSignatureSpan">gl-matrix.</span>quat
1.  object <span class="apidocSignatureSpan">gl-matrix.</span>vec2
1.  object <span class="apidocSignatureSpan">gl-matrix.</span>vec3
1.  object <span class="apidocSignatureSpan">gl-matrix.</span>vec4

#### [module gl-matrix.glMatrix](#apidoc.module.gl-matrix.glMatrix)
1.  boolean <span class="apidocSignatureSpan">gl-matrix.glMatrix.</span>ENABLE_SIMD
1.  boolean <span class="apidocSignatureSpan">gl-matrix.glMatrix.</span>SIMD_AVAILABLE
1.  boolean <span class="apidocSignatureSpan">gl-matrix.glMatrix.</span>USE_SIMD
1.  [function <span class="apidocSignatureSpan">gl-matrix.glMatrix.</span>ARRAY_TYPE ()](#apidoc.element.gl-matrix.glMatrix.ARRAY_TYPE)
1.  [function <span class="apidocSignatureSpan">gl-matrix.glMatrix.</span>RANDOM ()](#apidoc.element.gl-matrix.glMatrix.RANDOM)
1.  [function <span class="apidocSignatureSpan">gl-matrix.glMatrix.</span>equals (a, b)](#apidoc.element.gl-matrix.glMatrix.equals)
1.  [function <span class="apidocSignatureSpan">gl-matrix.glMatrix.</span>setMatrixArrayType (type)](#apidoc.element.gl-matrix.glMatrix.setMatrixArrayType)
1.  [function <span class="apidocSignatureSpan">gl-matrix.glMatrix.</span>toRadian (a)](#apidoc.element.gl-matrix.glMatrix.toRadian)
1.  number <span class="apidocSignatureSpan">gl-matrix.glMatrix.</span>EPSILON

#### [module gl-matrix.mat2](#apidoc.module.gl-matrix.mat2)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>LDU (L, D, U, a)](#apidoc.element.gl-matrix.mat2.LDU)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>add (out, a, b)](#apidoc.element.gl-matrix.mat2.add)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>adjoint (out, a)](#apidoc.element.gl-matrix.mat2.adjoint)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>clone (a)](#apidoc.element.gl-matrix.mat2.clone)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>copy (out, a)](#apidoc.element.gl-matrix.mat2.copy)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>create ()](#apidoc.element.gl-matrix.mat2.create)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>determinant (a)](#apidoc.element.gl-matrix.mat2.determinant)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>equals (a, b)](#apidoc.element.gl-matrix.mat2.equals)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>exactEquals (a, b)](#apidoc.element.gl-matrix.mat2.exactEquals)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>frob (a)](#apidoc.element.gl-matrix.mat2.frob)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>fromRotation (out, rad)](#apidoc.element.gl-matrix.mat2.fromRotation)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>fromScaling (out, v)](#apidoc.element.gl-matrix.mat2.fromScaling)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>fromValues (m00, m01, m10, m11)](#apidoc.element.gl-matrix.mat2.fromValues)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>identity (out)](#apidoc.element.gl-matrix.mat2.identity)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>invert (out, a)](#apidoc.element.gl-matrix.mat2.invert)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>mul (out, a, b)](#apidoc.element.gl-matrix.mat2.mul)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>multiply (out, a, b)](#apidoc.element.gl-matrix.mat2.multiply)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>multiplyScalar (out, a, b)](#apidoc.element.gl-matrix.mat2.multiplyScalar)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>multiplyScalarAndAdd (out, a, b, scale)](#apidoc.element.gl-matrix.mat2.multiplyScalarAndAdd)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>rotate (out, a, rad)](#apidoc.element.gl-matrix.mat2.rotate)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>scale (out, a, v)](#apidoc.element.gl-matrix.mat2.scale)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>set (out, m00, m01, m10, m11)](#apidoc.element.gl-matrix.mat2.set)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>str (a)](#apidoc.element.gl-matrix.mat2.str)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>sub (out, a, b)](#apidoc.element.gl-matrix.mat2.sub)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>subtract (out, a, b)](#apidoc.element.gl-matrix.mat2.subtract)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>transpose (out, a)](#apidoc.element.gl-matrix.mat2.transpose)

#### [module gl-matrix.mat2d](#apidoc.module.gl-matrix.mat2d)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>add (out, a, b)](#apidoc.element.gl-matrix.mat2d.add)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>clone (a)](#apidoc.element.gl-matrix.mat2d.clone)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>copy (out, a)](#apidoc.element.gl-matrix.mat2d.copy)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>create ()](#apidoc.element.gl-matrix.mat2d.create)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>determinant (a)](#apidoc.element.gl-matrix.mat2d.determinant)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>equals (a, b)](#apidoc.element.gl-matrix.mat2d.equals)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>exactEquals (a, b)](#apidoc.element.gl-matrix.mat2d.exactEquals)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>frob (a)](#apidoc.element.gl-matrix.mat2d.frob)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>fromRotation (out, rad)](#apidoc.element.gl-matrix.mat2d.fromRotation)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>fromScaling (out, v)](#apidoc.element.gl-matrix.mat2d.fromScaling)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>fromTranslation (out, v)](#apidoc.element.gl-matrix.mat2d.fromTranslation)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>fromValues (a, b, c, d, tx, ty)](#apidoc.element.gl-matrix.mat2d.fromValues)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>identity (out)](#apidoc.element.gl-matrix.mat2d.identity)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>invert (out, a)](#apidoc.element.gl-matrix.mat2d.invert)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>mul (out, a, b)](#apidoc.element.gl-matrix.mat2d.mul)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>multiply (out, a, b)](#apidoc.element.gl-matrix.mat2d.multiply)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>multiplyScalar (out, a, b)](#apidoc.element.gl-matrix.mat2d.multiplyScalar)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>multiplyScalarAndAdd (out, a, b, scale)](#apidoc.element.gl-matrix.mat2d.multiplyScalarAndAdd)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>rotate (out, a, rad)](#apidoc.element.gl-matrix.mat2d.rotate)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>scale (out, a, v)](#apidoc.element.gl-matrix.mat2d.scale)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>set (out, a, b, c, d, tx, ty)](#apidoc.element.gl-matrix.mat2d.set)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>str (a)](#apidoc.element.gl-matrix.mat2d.str)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>sub (out, a, b)](#apidoc.element.gl-matrix.mat2d.sub)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>subtract (out, a, b)](#apidoc.element.gl-matrix.mat2d.subtract)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>translate (out, a, v)](#apidoc.element.gl-matrix.mat2d.translate)

#### [module gl-matrix.mat3](#apidoc.module.gl-matrix.mat3)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>add (out, a, b)](#apidoc.element.gl-matrix.mat3.add)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>adjoint (out, a)](#apidoc.element.gl-matrix.mat3.adjoint)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>clone (a)](#apidoc.element.gl-matrix.mat3.clone)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>copy (out, a)](#apidoc.element.gl-matrix.mat3.copy)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>create ()](#apidoc.element.gl-matrix.mat3.create)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>determinant (a)](#apidoc.element.gl-matrix.mat3.determinant)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>equals (a, b)](#apidoc.element.gl-matrix.mat3.equals)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>exactEquals (a, b)](#apidoc.element.gl-matrix.mat3.exactEquals)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>frob (a)](#apidoc.element.gl-matrix.mat3.frob)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>fromMat2d (out, a)](#apidoc.element.gl-matrix.mat3.fromMat2d)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>fromMat4 (out, a)](#apidoc.element.gl-matrix.mat3.fromMat4)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>fromQuat (out, q)](#apidoc.element.gl-matrix.mat3.fromQuat)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>fromRotation (out, rad)](#apidoc.element.gl-matrix.mat3.fromRotation)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>fromScaling (out, v)](#apidoc.element.gl-matrix.mat3.fromScaling)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>fromTranslation (out, v)](#apidoc.element.gl-matrix.mat3.fromTranslation)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>fromValues (m00, m01, m02, m10, m11, m12, m20, m21, m22)](#apidoc.element.gl-matrix.mat3.fromValues)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>identity (out)](#apidoc.element.gl-matrix.mat3.identity)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>invert (out, a)](#apidoc.element.gl-matrix.mat3.invert)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>mul (out, a, b)](#apidoc.element.gl-matrix.mat3.mul)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>multiply (out, a, b)](#apidoc.element.gl-matrix.mat3.multiply)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>multiplyScalar (out, a, b)](#apidoc.element.gl-matrix.mat3.multiplyScalar)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>multiplyScalarAndAdd (out, a, b, scale)](#apidoc.element.gl-matrix.mat3.multiplyScalarAndAdd)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>normalFromMat4 (out, a)](#apidoc.element.gl-matrix.mat3.normalFromMat4)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>rotate (out, a, rad)](#apidoc.element.gl-matrix.mat3.rotate)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>scale (out, a, v)](#apidoc.element.gl-matrix.mat3.scale)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>set (out, m00, m01, m02, m10, m11, m12, m20, m21, m22)](#apidoc.element.gl-matrix.mat3.set)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>str (a)](#apidoc.element.gl-matrix.mat3.str)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>sub (out, a, b)](#apidoc.element.gl-matrix.mat3.sub)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>subtract (out, a, b)](#apidoc.element.gl-matrix.mat3.subtract)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>translate (out, a, v)](#apidoc.element.gl-matrix.mat3.translate)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>transpose (out, a)](#apidoc.element.gl-matrix.mat3.transpose)

#### [module gl-matrix.mat4](#apidoc.module.gl-matrix.mat4)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>add (out, a, b)](#apidoc.element.gl-matrix.mat4.add)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>adjoint (out, a)](#apidoc.element.gl-matrix.mat4.adjoint)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>clone (a)](#apidoc.element.gl-matrix.mat4.clone)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>copy (out, a)](#apidoc.element.gl-matrix.mat4.copy)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>create ()](#apidoc.element.gl-matrix.mat4.create)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>determinant (a)](#apidoc.element.gl-matrix.mat4.determinant)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>equals (a, b)](#apidoc.element.gl-matrix.mat4.equals)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>exactEquals (a, b)](#apidoc.element.gl-matrix.mat4.exactEquals)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>frob (a)](#apidoc.element.gl-matrix.mat4.frob)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>fromQuat (out, q)](#apidoc.element.gl-matrix.mat4.fromQuat)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>fromRotation (out, rad, axis)](#apidoc.element.gl-matrix.mat4.fromRotation)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>fromRotationTranslation (out, q, v)](#apidoc.element.gl-matrix.mat4.fromRotationTranslation)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>fromRotationTranslationScale (out, q, v, s)](#apidoc.element.gl-matrix.mat4.fromRotationTranslationScale)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>fromRotationTranslationScaleOrigin (out, q, v, s, o)](#apidoc.element.gl-matrix.mat4.fromRotationTranslationScaleOrigin)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>fromScaling (out, v)](#apidoc.element.gl-matrix.mat4.fromScaling)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>fromTranslation (out, v)](#apidoc.element.gl-matrix.mat4.fromTranslation)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>fromValues (m00, m01, m02, m03, m10, m11, m12, m13, m20, m21, m22, m23, m30, m31, m32, m33)](#apidoc.element.gl-matrix.mat4.fromValues)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>fromXRotation (out, rad)](#apidoc.element.gl-matrix.mat4.fromXRotation)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>fromYRotation (out, rad)](#apidoc.element.gl-matrix.mat4.fromYRotation)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>fromZRotation (out, rad)](#apidoc.element.gl-matrix.mat4.fromZRotation)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>frustum (out, left, right, bottom, top, near, far)](#apidoc.element.gl-matrix.mat4.frustum)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>getRotation (out, mat)](#apidoc.element.gl-matrix.mat4.getRotation)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>getTranslation (out, mat)](#apidoc.element.gl-matrix.mat4.getTranslation)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>identity (out)](#apidoc.element.gl-matrix.mat4.identity)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>invert (out, a)](#apidoc.element.gl-matrix.mat4.invert)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>lookAt (out, eye, center, up)](#apidoc.element.gl-matrix.mat4.lookAt)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>mul (out, a, b)](#apidoc.element.gl-matrix.mat4.mul)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>multiply (out, a, b)](#apidoc.element.gl-matrix.mat4.multiply)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>multiplyScalar (out, a, b)](#apidoc.element.gl-matrix.mat4.multiplyScalar)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>multiplyScalarAndAdd (out, a, b, scale)](#apidoc.element.gl-matrix.mat4.multiplyScalarAndAdd)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>ortho (out, left, right, bottom, top, near, far)](#apidoc.element.gl-matrix.mat4.ortho)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>perspective (out, fovy, aspect, near, far)](#apidoc.element.gl-matrix.mat4.perspective)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>perspectiveFromFieldOfView (out, fov, near, far)](#apidoc.element.gl-matrix.mat4.perspectiveFromFieldOfView)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>rotate (out, a, rad, axis)](#apidoc.element.gl-matrix.mat4.rotate)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>rotateX (out, a, rad)](#apidoc.element.gl-matrix.mat4.rotateX)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>rotateY (out, a, rad)](#apidoc.element.gl-matrix.mat4.rotateY)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>rotateZ (out, a, rad)](#apidoc.element.gl-matrix.mat4.rotateZ)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>scale (out, a, v)](#apidoc.element.gl-matrix.mat4.scale)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>set (out, m00, m01, m02, m03, m10, m11, m12, m13, m20, m21, m22, m23, m30, m31, m32, m33)](#apidoc.element.gl-matrix.mat4.set)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>str (a)](#apidoc.element.gl-matrix.mat4.str)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>sub (out, a, b)](#apidoc.element.gl-matrix.mat4.sub)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>subtract (out, a, b)](#apidoc.element.gl-matrix.mat4.subtract)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>translate (out, a, v)](#apidoc.element.gl-matrix.mat4.translate)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>transpose (out, a)](#apidoc.element.gl-matrix.mat4.transpose)
1.  object <span class="apidocSignatureSpan">gl-matrix.mat4.</span>SIMD
1.  object <span class="apidocSignatureSpan">gl-matrix.mat4.</span>scalar

#### [module gl-matrix.mat4.SIMD](#apidoc.module.gl-matrix.mat4.SIMD)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.SIMD.</span>adjoint (out, a)](#apidoc.element.gl-matrix.mat4.SIMD.adjoint)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.SIMD.</span>invert (out, a)](#apidoc.element.gl-matrix.mat4.SIMD.invert)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.SIMD.</span>multiply (out, a, b)](#apidoc.element.gl-matrix.mat4.SIMD.multiply)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.SIMD.</span>rotateX (out, a, rad)](#apidoc.element.gl-matrix.mat4.SIMD.rotateX)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.SIMD.</span>rotateY (out, a, rad)](#apidoc.element.gl-matrix.mat4.SIMD.rotateY)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.SIMD.</span>rotateZ (out, a, rad)](#apidoc.element.gl-matrix.mat4.SIMD.rotateZ)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.SIMD.</span>scale (out, a, v)](#apidoc.element.gl-matrix.mat4.SIMD.scale)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.SIMD.</span>translate (out, a, v)](#apidoc.element.gl-matrix.mat4.SIMD.translate)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.SIMD.</span>transpose (out, a)](#apidoc.element.gl-matrix.mat4.SIMD.transpose)

#### [module gl-matrix.mat4.scalar](#apidoc.module.gl-matrix.mat4.scalar)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.scalar.</span>adjoint (out, a)](#apidoc.element.gl-matrix.mat4.scalar.adjoint)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.scalar.</span>invert (out, a)](#apidoc.element.gl-matrix.mat4.scalar.invert)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.scalar.</span>multiply (out, a, b)](#apidoc.element.gl-matrix.mat4.scalar.multiply)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.scalar.</span>rotateX (out, a, rad)](#apidoc.element.gl-matrix.mat4.scalar.rotateX)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.scalar.</span>rotateY (out, a, rad)](#apidoc.element.gl-matrix.mat4.scalar.rotateY)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.scalar.</span>rotateZ (out, a, rad)](#apidoc.element.gl-matrix.mat4.scalar.rotateZ)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.scalar.</span>scale (out, a, v)](#apidoc.element.gl-matrix.mat4.scalar.scale)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.scalar.</span>translate (out, a, v)](#apidoc.element.gl-matrix.mat4.scalar.translate)
1.  [function <span class="apidocSignatureSpan">gl-matrix.mat4.scalar.</span>transpose (out, a)](#apidoc.element.gl-matrix.mat4.scalar.transpose)

#### [module gl-matrix.quat](#apidoc.module.gl-matrix.quat)
1.  [function <span class="apidocSignatureSpan">gl-matrix.quat.</span>add (out, a, b)](#apidoc.element.gl-matrix.quat.add)
1.  [function <span class="apidocSignatureSpan">gl-matrix.quat.</span>calculateW (out, a)](#apidoc.element.gl-matrix.quat.calculateW)
1.  [function <span class="apidocSignatureSpan">gl-matrix.quat.</span>clone (a)](#apidoc.element.gl-matrix.quat.clone)
1.  [function <span class="apidocSignatureSpan">gl-matrix.quat.</span>conjugate (out, a)](#apidoc.element.gl-matrix.quat.conjugate)
1.  [function <span class="apidocSignatureSpan">gl-matrix.quat.</span>copy (out, a)](#apidoc.element.gl-matrix.quat.copy)
1.  [function <span class="apidocSignatureSpan">gl-matrix.quat.</span>create ()](#apidoc.element.gl-matrix.quat.create)
1.  [function <span class="apidocSignatureSpan">gl-matrix.quat.</span>dot (a, b)](#apidoc.element.gl-matrix.quat.dot)
1.  [function <span class="apidocSignatureSpan">gl-matrix.quat.</span>equals (a, b)](#apidoc.element.gl-matrix.quat.equals)
1.  [function <span class="apidocSignatureSpan">gl-matrix.quat.</span>exactEquals (a, b)](#apidoc.element.gl-matrix.quat.exactEquals)
1.  [function <span class="apidocSignatureSpan">gl-matrix.quat.</span>fromMat3 (out, m)](#apidoc.element.gl-matrix.quat.fromMat3)
1.  [function <span class="apidocSignatureSpan">gl-matrix.quat.</span>fromValues (x, y, z, w)](#apidoc.element.gl-matrix.quat.fromValues)
1.  [function <span class="apidocSignatureSpan">gl-matrix.quat.</span>getAxisAngle (out_axis, q)](#apidoc.element.gl-matrix.quat.getAxisAngle)
1.  [function <span class="apidocSignatureSpan">gl-matrix.quat.</span>identity (out)](#apidoc.element.gl-matrix.quat.identity)
1.  [function <span class="apidocSignatureSpan">gl-matrix.quat.</span>invert (out, a)](#apidoc.element.gl-matrix.quat.invert)
1.  [function <span class="apidocSignatureSpan">gl-matrix.quat.</span>len (a)](#apidoc.element.gl-matrix.quat.len)
1.  [function <span class="apidocSignatureSpan">gl-matrix.quat.</span>length (a)](#apidoc.element.gl-matrix.quat.length)
1.  [function <span class="apidocSignatureSpan">gl-matrix.quat.</span>lerp (out, a, b, t)](#apidoc.element.gl-matrix.quat.lerp)
1.  [function <span class="apidocSignatureSpan">gl-matrix.quat.</span>mul (out, a, b)](#apidoc.element.gl-matrix.quat.mul)
1.  [function <span class="apidocSignatureSpan">gl-matrix.quat.</span>multiply (out, a, b)](#apidoc.element.gl-matrix.quat.multiply)
1.  [function <span class="apidocSignatureSpan">gl-matrix.quat.</span>normalize (out, a)](#apidoc.element.gl-matrix.quat.normalize)
1.  [function <span class="apidocSignatureSpan">gl-matrix.quat.</span>rotateX (out, a, rad)](#apidoc.element.gl-matrix.quat.rotateX)
1.  [function <span class="apidocSignatureSpan">gl-matrix.quat.</span>rotateY (out, a, rad)](#apidoc.element.gl-matrix.quat.rotateY)
1.  [function <span class="apidocSignatureSpan">gl-matrix.quat.</span>rotateZ (out, a, rad)](#apidoc.element.gl-matrix.quat.rotateZ)
1.  [function <span class="apidocSignatureSpan">gl-matrix.quat.</span>rotationTo (out, a, b)](#apidoc.element.gl-matrix.quat.rotationTo)
1.  [function <span class="apidocSignatureSpan">gl-matrix.quat.</span>scale (out, a, b)](#apidoc.element.gl-matrix.quat.scale)
1.  [function <span class="apidocSignatureSpan">gl-matrix.quat.</span>set (out, x, y, z, w)](#apidoc.element.gl-matrix.quat.set)
1.  [function <span class="apidocSignatureSpan">gl-matrix.quat.</span>setAxes (out, view, right, up)](#apidoc.element.gl-matrix.quat.setAxes)
1.  [function <span class="apidocSignatureSpan">gl-matrix.quat.</span>setAxisAngle (out, axis, rad)](#apidoc.element.gl-matrix.quat.setAxisAngle)
1.  [function <span class="apidocSignatureSpan">gl-matrix.quat.</span>slerp (out, a, b, t)](#apidoc.element.gl-matrix.quat.slerp)
1.  [function <span class="apidocSignatureSpan">gl-matrix.quat.</span>sqlerp (out, a, b, c, d, t)](#apidoc.element.gl-matrix.quat.sqlerp)
1.  [function <span class="apidocSignatureSpan">gl-matrix.quat.</span>sqrLen (a)](#apidoc.element.gl-matrix.quat.sqrLen)
1.  [function <span class="apidocSignatureSpan">gl-matrix.quat.</span>squaredLength (a)](#apidoc.element.gl-matrix.quat.squaredLength)
1.  [function <span class="apidocSignatureSpan">gl-matrix.quat.</span>str (a)](#apidoc.element.gl-matrix.quat.str)

#### [module gl-matrix.vec2](#apidoc.module.gl-matrix.vec2)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>add (out, a, b)](#apidoc.element.gl-matrix.vec2.add)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>ceil (out, a)](#apidoc.element.gl-matrix.vec2.ceil)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>clone (a)](#apidoc.element.gl-matrix.vec2.clone)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>copy (out, a)](#apidoc.element.gl-matrix.vec2.copy)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>create ()](#apidoc.element.gl-matrix.vec2.create)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>cross (out, a, b)](#apidoc.element.gl-matrix.vec2.cross)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>dist (a, b)](#apidoc.element.gl-matrix.vec2.dist)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>distance (a, b)](#apidoc.element.gl-matrix.vec2.distance)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>div (out, a, b)](#apidoc.element.gl-matrix.vec2.div)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>divide (out, a, b)](#apidoc.element.gl-matrix.vec2.divide)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>dot (a, b)](#apidoc.element.gl-matrix.vec2.dot)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>equals (a, b)](#apidoc.element.gl-matrix.vec2.equals)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>exactEquals (a, b)](#apidoc.element.gl-matrix.vec2.exactEquals)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>floor (out, a)](#apidoc.element.gl-matrix.vec2.floor)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>forEach (a, stride, offset, count, fn, arg)](#apidoc.element.gl-matrix.vec2.forEach)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>fromValues (x, y)](#apidoc.element.gl-matrix.vec2.fromValues)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>inverse (out, a)](#apidoc.element.gl-matrix.vec2.inverse)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>len (a)](#apidoc.element.gl-matrix.vec2.len)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>length (a)](#apidoc.element.gl-matrix.vec2.length)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>lerp (out, a, b, t)](#apidoc.element.gl-matrix.vec2.lerp)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>max (out, a, b)](#apidoc.element.gl-matrix.vec2.max)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>min (out, a, b)](#apidoc.element.gl-matrix.vec2.min)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>mul (out, a, b)](#apidoc.element.gl-matrix.vec2.mul)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>multiply (out, a, b)](#apidoc.element.gl-matrix.vec2.multiply)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>negate (out, a)](#apidoc.element.gl-matrix.vec2.negate)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>normalize (out, a)](#apidoc.element.gl-matrix.vec2.normalize)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>random (out, scale)](#apidoc.element.gl-matrix.vec2.random)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>round (out, a)](#apidoc.element.gl-matrix.vec2.round)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>scale (out, a, b)](#apidoc.element.gl-matrix.vec2.scale)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>scaleAndAdd (out, a, b, scale)](#apidoc.element.gl-matrix.vec2.scaleAndAdd)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>set (out, x, y)](#apidoc.element.gl-matrix.vec2.set)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>sqrDist (a, b)](#apidoc.element.gl-matrix.vec2.sqrDist)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>sqrLen (a)](#apidoc.element.gl-matrix.vec2.sqrLen)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>squaredDistance (a, b)](#apidoc.element.gl-matrix.vec2.squaredDistance)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>squaredLength (a)](#apidoc.element.gl-matrix.vec2.squaredLength)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>str (a)](#apidoc.element.gl-matrix.vec2.str)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>sub (out, a, b)](#apidoc.element.gl-matrix.vec2.sub)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>subtract (out, a, b)](#apidoc.element.gl-matrix.vec2.subtract)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>transformMat2 (out, a, m)](#apidoc.element.gl-matrix.vec2.transformMat2)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>transformMat2d (out, a, m)](#apidoc.element.gl-matrix.vec2.transformMat2d)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>transformMat3 (out, a, m)](#apidoc.element.gl-matrix.vec2.transformMat3)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>transformMat4 (out, a, m)](#apidoc.element.gl-matrix.vec2.transformMat4)

#### [module gl-matrix.vec3](#apidoc.module.gl-matrix.vec3)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>add (out, a, b)](#apidoc.element.gl-matrix.vec3.add)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>angle (a, b)](#apidoc.element.gl-matrix.vec3.angle)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>bezier (out, a, b, c, d, t)](#apidoc.element.gl-matrix.vec3.bezier)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>ceil (out, a)](#apidoc.element.gl-matrix.vec3.ceil)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>clone (a)](#apidoc.element.gl-matrix.vec3.clone)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>copy (out, a)](#apidoc.element.gl-matrix.vec3.copy)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>create ()](#apidoc.element.gl-matrix.vec3.create)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>cross (out, a, b)](#apidoc.element.gl-matrix.vec3.cross)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>dist (a, b)](#apidoc.element.gl-matrix.vec3.dist)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>distance (a, b)](#apidoc.element.gl-matrix.vec3.distance)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>div (out, a, b)](#apidoc.element.gl-matrix.vec3.div)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>divide (out, a, b)](#apidoc.element.gl-matrix.vec3.divide)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>dot (a, b)](#apidoc.element.gl-matrix.vec3.dot)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>equals (a, b)](#apidoc.element.gl-matrix.vec3.equals)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>exactEquals (a, b)](#apidoc.element.gl-matrix.vec3.exactEquals)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>floor (out, a)](#apidoc.element.gl-matrix.vec3.floor)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>forEach (a, stride, offset, count, fn, arg)](#apidoc.element.gl-matrix.vec3.forEach)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>fromValues (x, y, z)](#apidoc.element.gl-matrix.vec3.fromValues)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>hermite (out, a, b, c, d, t)](#apidoc.element.gl-matrix.vec3.hermite)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>inverse (out, a)](#apidoc.element.gl-matrix.vec3.inverse)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>len (a)](#apidoc.element.gl-matrix.vec3.len)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>length (a)](#apidoc.element.gl-matrix.vec3.length)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>lerp (out, a, b, t)](#apidoc.element.gl-matrix.vec3.lerp)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>max (out, a, b)](#apidoc.element.gl-matrix.vec3.max)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>min (out, a, b)](#apidoc.element.gl-matrix.vec3.min)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>mul (out, a, b)](#apidoc.element.gl-matrix.vec3.mul)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>multiply (out, a, b)](#apidoc.element.gl-matrix.vec3.multiply)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>negate (out, a)](#apidoc.element.gl-matrix.vec3.negate)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>normalize (out, a)](#apidoc.element.gl-matrix.vec3.normalize)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>random (out, scale)](#apidoc.element.gl-matrix.vec3.random)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>rotateX (out, a, b, c)](#apidoc.element.gl-matrix.vec3.rotateX)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>rotateY (out, a, b, c)](#apidoc.element.gl-matrix.vec3.rotateY)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>rotateZ (out, a, b, c)](#apidoc.element.gl-matrix.vec3.rotateZ)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>round (out, a)](#apidoc.element.gl-matrix.vec3.round)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>scale (out, a, b)](#apidoc.element.gl-matrix.vec3.scale)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>scaleAndAdd (out, a, b, scale)](#apidoc.element.gl-matrix.vec3.scaleAndAdd)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>set (out, x, y, z)](#apidoc.element.gl-matrix.vec3.set)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>sqrDist (a, b)](#apidoc.element.gl-matrix.vec3.sqrDist)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>sqrLen (a)](#apidoc.element.gl-matrix.vec3.sqrLen)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>squaredDistance (a, b)](#apidoc.element.gl-matrix.vec3.squaredDistance)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>squaredLength (a)](#apidoc.element.gl-matrix.vec3.squaredLength)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>str (a)](#apidoc.element.gl-matrix.vec3.str)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>sub (out, a, b)](#apidoc.element.gl-matrix.vec3.sub)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>subtract (out, a, b)](#apidoc.element.gl-matrix.vec3.subtract)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>transformMat3 (out, a, m)](#apidoc.element.gl-matrix.vec3.transformMat3)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>transformMat4 (out, a, m)](#apidoc.element.gl-matrix.vec3.transformMat4)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>transformQuat (out, a, q)](#apidoc.element.gl-matrix.vec3.transformQuat)

#### [module gl-matrix.vec4](#apidoc.module.gl-matrix.vec4)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>add (out, a, b)](#apidoc.element.gl-matrix.vec4.add)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>ceil (out, a)](#apidoc.element.gl-matrix.vec4.ceil)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>clone (a)](#apidoc.element.gl-matrix.vec4.clone)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>copy (out, a)](#apidoc.element.gl-matrix.vec4.copy)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>create ()](#apidoc.element.gl-matrix.vec4.create)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>dist (a, b)](#apidoc.element.gl-matrix.vec4.dist)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>distance (a, b)](#apidoc.element.gl-matrix.vec4.distance)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>div (out, a, b)](#apidoc.element.gl-matrix.vec4.div)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>divide (out, a, b)](#apidoc.element.gl-matrix.vec4.divide)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>dot (a, b)](#apidoc.element.gl-matrix.vec4.dot)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>equals (a, b)](#apidoc.element.gl-matrix.vec4.equals)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>exactEquals (a, b)](#apidoc.element.gl-matrix.vec4.exactEquals)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>floor (out, a)](#apidoc.element.gl-matrix.vec4.floor)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>forEach (a, stride, offset, count, fn, arg)](#apidoc.element.gl-matrix.vec4.forEach)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>fromValues (x, y, z, w)](#apidoc.element.gl-matrix.vec4.fromValues)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>inverse (out, a)](#apidoc.element.gl-matrix.vec4.inverse)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>len (a)](#apidoc.element.gl-matrix.vec4.len)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>length (a)](#apidoc.element.gl-matrix.vec4.length)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>lerp (out, a, b, t)](#apidoc.element.gl-matrix.vec4.lerp)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>max (out, a, b)](#apidoc.element.gl-matrix.vec4.max)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>min (out, a, b)](#apidoc.element.gl-matrix.vec4.min)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>mul (out, a, b)](#apidoc.element.gl-matrix.vec4.mul)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>multiply (out, a, b)](#apidoc.element.gl-matrix.vec4.multiply)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>negate (out, a)](#apidoc.element.gl-matrix.vec4.negate)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>normalize (out, a)](#apidoc.element.gl-matrix.vec4.normalize)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>random (out, scale)](#apidoc.element.gl-matrix.vec4.random)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>round (out, a)](#apidoc.element.gl-matrix.vec4.round)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>scale (out, a, b)](#apidoc.element.gl-matrix.vec4.scale)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>scaleAndAdd (out, a, b, scale)](#apidoc.element.gl-matrix.vec4.scaleAndAdd)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>set (out, x, y, z, w)](#apidoc.element.gl-matrix.vec4.set)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>sqrDist (a, b)](#apidoc.element.gl-matrix.vec4.sqrDist)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>sqrLen (a)](#apidoc.element.gl-matrix.vec4.sqrLen)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>squaredDistance (a, b)](#apidoc.element.gl-matrix.vec4.squaredDistance)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>squaredLength (a)](#apidoc.element.gl-matrix.vec4.squaredLength)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>str (a)](#apidoc.element.gl-matrix.vec4.str)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>sub (out, a, b)](#apidoc.element.gl-matrix.vec4.sub)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>subtract (out, a, b)](#apidoc.element.gl-matrix.vec4.subtract)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>transformMat4 (out, a, m)](#apidoc.element.gl-matrix.vec4.transformMat4)
1.  [function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>transformQuat (out, a, q)](#apidoc.element.gl-matrix.vec4.transformQuat)



# <a name="apidoc.module.gl-matrix"></a>[module gl-matrix](#apidoc.module.gl-matrix)



# <a name="apidoc.module.gl-matrix.glMatrix"></a>[module gl-matrix.glMatrix](#apidoc.module.gl-matrix.glMatrix)

#### <a name="apidoc.element.gl-matrix.glMatrix.ARRAY_TYPE"></a>[function <span class="apidocSignatureSpan">gl-matrix.glMatrix.</span>ARRAY_TYPE ()](#apidoc.element.gl-matrix.glMatrix.ARRAY_TYPE)
- description and source-code
```javascript
function Float32Array() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.glMatrix.RANDOM"></a>[function <span class="apidocSignatureSpan">gl-matrix.glMatrix.</span>RANDOM ()](#apidoc.element.gl-matrix.glMatrix.RANDOM)
- description and source-code
```javascript
function random() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.glMatrix.equals"></a>[function <span class="apidocSignatureSpan">gl-matrix.glMatrix.</span>equals (a, b)](#apidoc.element.gl-matrix.glMatrix.equals)
- description and source-code
```javascript
equals = function (a, b) {
	return Math.abs(a - b) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a), Math.abs(b));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.glMatrix.setMatrixArrayType"></a>[function <span class="apidocSignatureSpan">gl-matrix.glMatrix.</span>setMatrixArrayType (type)](#apidoc.element.gl-matrix.glMatrix.setMatrixArrayType)
- description and source-code
```javascript
setMatrixArrayType = function (type) {
    glMatrix.ARRAY_TYPE = type;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.glMatrix.toRadian"></a>[function <span class="apidocSignatureSpan">gl-matrix.glMatrix.</span>toRadian (a)](#apidoc.element.gl-matrix.glMatrix.toRadian)
- description and source-code
```javascript
toRadian = function (a){
     return a * degree;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gl-matrix.mat2"></a>[module gl-matrix.mat2](#apidoc.module.gl-matrix.mat2)

#### <a name="apidoc.element.gl-matrix.mat2.LDU"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>LDU (L, D, U, a)](#apidoc.element.gl-matrix.mat2.LDU)
- description and source-code
```javascript
LDU = function (L, D, U, a) {
    L[2] = a[2]/a[0];
    U[0] = a[0];
    U[1] = a[1];
    U[3] = a[3] - L[2] * U[1];
    return [L, D, U];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2.add"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>add (out, a, b)](#apidoc.element.gl-matrix.mat2.add)
- description and source-code
```javascript
add = function (out, a, b) {
    out[0] = a[0] + b[0];
    out[1] = a[1] + b[1];
    out[2] = a[2] + b[2];
    out[3] = a[3] + b[3];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2.adjoint"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>adjoint (out, a)](#apidoc.element.gl-matrix.mat2.adjoint)
- description and source-code
```javascript
adjoint = function (out, a) {
    // Caching this value is nessecary if out == a
    var a0 = a[0];
    out[0] =  a[3];
    out[1] = -a[1];
    out[2] = -a[2];
    out[3] =  a0;

    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2.clone"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>clone (a)](#apidoc.element.gl-matrix.mat2.clone)
- description and source-code
```javascript
clone = function (a) {
    var out = new glMatrix.ARRAY_TYPE(4);
    out[0] = a[0];
    out[1] = a[1];
    out[2] = a[2];
    out[3] = a[3];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2.copy"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>copy (out, a)](#apidoc.element.gl-matrix.mat2.copy)
- description and source-code
```javascript
copy = function (out, a) {
    out[0] = a[0];
    out[1] = a[1];
    out[2] = a[2];
    out[3] = a[3];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2.create"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>create ()](#apidoc.element.gl-matrix.mat2.create)
- description and source-code
```javascript
create = function () {
    var out = new glMatrix.ARRAY_TYPE(4);
    out[0] = 1;
    out[1] = 0;
    out[2] = 0;
    out[3] = 1;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2.determinant"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>determinant (a)](#apidoc.element.gl-matrix.mat2.determinant)
- description and source-code
```javascript
determinant = function (a) {
    return a[0] * a[3] - a[2] * a[1];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2.equals"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>equals (a, b)](#apidoc.element.gl-matrix.mat2.equals)
- description and source-code
```javascript
equals = function (a, b) {
    var a0 = a[0], a1 = a[1], a2 = a[2], a3 = a[3];
    var b0 = b[0], b1 = b[1], b2 = b[2], b3 = b[3];
    return (Math.abs(a0 - b0) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a0), Math.abs(b0)) &&
            Math.abs(a1 - b1) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a1), Math.abs(b1)) &&
            Math.abs(a2 - b2) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a2), Math.abs(b2)) &&
            Math.abs(a3 - b3) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a3), Math.abs(b3)));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2.exactEquals"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>exactEquals (a, b)](#apidoc.element.gl-matrix.mat2.exactEquals)
- description and source-code
```javascript
exactEquals = function (a, b) {
    return a[0] === b[0] && a[1] === b[1] && a[2] === b[2] && a[3] === b[3];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2.frob"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>frob (a)](#apidoc.element.gl-matrix.mat2.frob)
- description and source-code
```javascript
frob = function (a) {
    return(Math.sqrt(Math.pow(a[0], 2) + Math.pow(a[1], 2) + Math.pow(a[2], 2) + Math.pow(a[3], 2)))
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2.fromRotation"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>fromRotation (out, rad)](#apidoc.element.gl-matrix.mat2.fromRotation)
- description and source-code
```javascript
fromRotation = function (out, rad) {
    var s = Math.sin(rad),
        c = Math.cos(rad);
    out[0] = c;
    out[1] = s;
    out[2] = -s;
    out[3] = c;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2.fromScaling"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>fromScaling (out, v)](#apidoc.element.gl-matrix.mat2.fromScaling)
- description and source-code
```javascript
fromScaling = function (out, v) {
    out[0] = v[0];
    out[1] = 0;
    out[2] = 0;
    out[3] = v[1];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2.fromValues"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>fromValues (m00, m01, m10, m11)](#apidoc.element.gl-matrix.mat2.fromValues)
- description and source-code
```javascript
fromValues = function (m00, m01, m10, m11) {
    var out = new glMatrix.ARRAY_TYPE(4);
    out[0] = m00;
    out[1] = m01;
    out[2] = m10;
    out[3] = m11;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2.identity"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>identity (out)](#apidoc.element.gl-matrix.mat2.identity)
- description and source-code
```javascript
identity = function (out) {
    out[0] = 1;
    out[1] = 0;
    out[2] = 0;
    out[3] = 1;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2.invert"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>invert (out, a)](#apidoc.element.gl-matrix.mat2.invert)
- description and source-code
```javascript
invert = function (out, a) {
    var a0 = a[0], a1 = a[1], a2 = a[2], a3 = a[3],

        // Calculate the determinant
        det = a0 * a3 - a2 * a1;

    if (!det) {
        return null;
    }
    det = 1.0 / det;

    out[0] =  a3 * det;
    out[1] = -a1 * det;
    out[2] = -a2 * det;
    out[3] =  a0 * det;

    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2.mul"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>mul (out, a, b)](#apidoc.element.gl-matrix.mat2.mul)
- description and source-code
```javascript
mul = function (out, a, b) {
    var a0 = a[0], a1 = a[1], a2 = a[2], a3 = a[3];
    var b0 = b[0], b1 = b[1], b2 = b[2], b3 = b[3];
    out[0] = a0 * b0 + a2 * b1;
    out[1] = a1 * b0 + a3 * b1;
    out[2] = a0 * b2 + a2 * b3;
    out[3] = a1 * b2 + a3 * b3;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2.multiply"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>multiply (out, a, b)](#apidoc.element.gl-matrix.mat2.multiply)
- description and source-code
```javascript
multiply = function (out, a, b) {
    var a0 = a[0], a1 = a[1], a2 = a[2], a3 = a[3];
    var b0 = b[0], b1 = b[1], b2 = b[2], b3 = b[3];
    out[0] = a0 * b0 + a2 * b1;
    out[1] = a1 * b0 + a3 * b1;
    out[2] = a0 * b2 + a2 * b3;
    out[3] = a1 * b2 + a3 * b3;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2.multiplyScalar"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>multiplyScalar (out, a, b)](#apidoc.element.gl-matrix.mat2.multiplyScalar)
- description and source-code
```javascript
multiplyScalar = function (out, a, b) {
    out[0] = a[0] * b;
    out[1] = a[1] * b;
    out[2] = a[2] * b;
    out[3] = a[3] * b;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2.multiplyScalarAndAdd"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>multiplyScalarAndAdd (out, a, b, scale)](#apidoc.element.gl-matrix.mat2.multiplyScalarAndAdd)
- description and source-code
```javascript
multiplyScalarAndAdd = function (out, a, b, scale) {
    out[0] = a[0] + (b[0] * scale);
    out[1] = a[1] + (b[1] * scale);
    out[2] = a[2] + (b[2] * scale);
    out[3] = a[3] + (b[3] * scale);
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2.rotate"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>rotate (out, a, rad)](#apidoc.element.gl-matrix.mat2.rotate)
- description and source-code
```javascript
rotate = function (out, a, rad) {
    var a0 = a[0], a1 = a[1], a2 = a[2], a3 = a[3],
        s = Math.sin(rad),
        c = Math.cos(rad);
    out[0] = a0 *  c + a2 * s;
    out[1] = a1 *  c + a3 * s;
    out[2] = a0 * -s + a2 * c;
    out[3] = a1 * -s + a3 * c;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2.scale"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>scale (out, a, v)](#apidoc.element.gl-matrix.mat2.scale)
- description and source-code
```javascript
scale = function (out, a, v) {
    var a0 = a[0], a1 = a[1], a2 = a[2], a3 = a[3],
        v0 = v[0], v1 = v[1];
    out[0] = a0 * v0;
    out[1] = a1 * v0;
    out[2] = a2 * v1;
    out[3] = a3 * v1;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2.set"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>set (out, m00, m01, m10, m11)](#apidoc.element.gl-matrix.mat2.set)
- description and source-code
```javascript
set = function (out, m00, m01, m10, m11) {
    out[0] = m00;
    out[1] = m01;
    out[2] = m10;
    out[3] = m11;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2.str"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>str (a)](#apidoc.element.gl-matrix.mat2.str)
- description and source-code
```javascript
str = function (a) {
    return 'mat2(' + a[0] + ', ' + a[1] + ', ' + a[2] + ', ' + a[3] + ')';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2.sub"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>sub (out, a, b)](#apidoc.element.gl-matrix.mat2.sub)
- description and source-code
```javascript
sub = function (out, a, b) {
    out[0] = a[0] - b[0];
    out[1] = a[1] - b[1];
    out[2] = a[2] - b[2];
    out[3] = a[3] - b[3];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2.subtract"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>subtract (out, a, b)](#apidoc.element.gl-matrix.mat2.subtract)
- description and source-code
```javascript
subtract = function (out, a, b) {
    out[0] = a[0] - b[0];
    out[1] = a[1] - b[1];
    out[2] = a[2] - b[2];
    out[3] = a[3] - b[3];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2.transpose"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2.</span>transpose (out, a)](#apidoc.element.gl-matrix.mat2.transpose)
- description and source-code
```javascript
transpose = function (out, a) {
    // If we are transposing ourselves we can skip a few steps but have to cache some values
    if (out === a) {
        var a1 = a[1];
        out[1] = a[2];
        out[2] = a1;
    } else {
        out[0] = a[0];
        out[1] = a[2];
        out[2] = a[1];
        out[3] = a[3];
    }

    return out;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gl-matrix.mat2d"></a>[module gl-matrix.mat2d](#apidoc.module.gl-matrix.mat2d)

#### <a name="apidoc.element.gl-matrix.mat2d.add"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>add (out, a, b)](#apidoc.element.gl-matrix.mat2d.add)
- description and source-code
```javascript
add = function (out, a, b) {
    out[0] = a[0] + b[0];
    out[1] = a[1] + b[1];
    out[2] = a[2] + b[2];
    out[3] = a[3] + b[3];
    out[4] = a[4] + b[4];
    out[5] = a[5] + b[5];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2d.clone"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>clone (a)](#apidoc.element.gl-matrix.mat2d.clone)
- description and source-code
```javascript
clone = function (a) {
    var out = new glMatrix.ARRAY_TYPE(6);
    out[0] = a[0];
    out[1] = a[1];
    out[2] = a[2];
    out[3] = a[3];
    out[4] = a[4];
    out[5] = a[5];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2d.copy"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>copy (out, a)](#apidoc.element.gl-matrix.mat2d.copy)
- description and source-code
```javascript
copy = function (out, a) {
    out[0] = a[0];
    out[1] = a[1];
    out[2] = a[2];
    out[3] = a[3];
    out[4] = a[4];
    out[5] = a[5];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2d.create"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>create ()](#apidoc.element.gl-matrix.mat2d.create)
- description and source-code
```javascript
create = function () {
    var out = new glMatrix.ARRAY_TYPE(6);
    out[0] = 1;
    out[1] = 0;
    out[2] = 0;
    out[3] = 1;
    out[4] = 0;
    out[5] = 0;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2d.determinant"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>determinant (a)](#apidoc.element.gl-matrix.mat2d.determinant)
- description and source-code
```javascript
determinant = function (a) {
    return a[0] * a[3] - a[1] * a[2];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2d.equals"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>equals (a, b)](#apidoc.element.gl-matrix.mat2d.equals)
- description and source-code
```javascript
equals = function (a, b) {
    var a0 = a[0], a1 = a[1], a2 = a[2], a3 = a[3], a4 = a[4], a5 = a[5];
    var b0 = b[0], b1 = b[1], b2 = b[2], b3 = b[3], b4 = b[4], b5 = b[5];
    return (Math.abs(a0 - b0) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a0), Math.abs(b0)) &&
            Math.abs(a1 - b1) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a1), Math.abs(b1)) &&
            Math.abs(a2 - b2) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a2), Math.abs(b2)) &&
            Math.abs(a3 - b3) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a3), Math.abs(b3)) &&
            Math.abs(a4 - b4) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a4), Math.abs(b4)) &&
            Math.abs(a5 - b5) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a5), Math.abs(b5)));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2d.exactEquals"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>exactEquals (a, b)](#apidoc.element.gl-matrix.mat2d.exactEquals)
- description and source-code
```javascript
exactEquals = function (a, b) {
    return a[0] === b[0] && a[1] === b[1] && a[2] === b[2] && a[3] === b[3] && a[4] === b[4] && a[5] === b[5];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2d.frob"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>frob (a)](#apidoc.element.gl-matrix.mat2d.frob)
- description and source-code
```javascript
frob = function (a) {
    return(Math.sqrt(Math.pow(a[0], 2) + Math.pow(a[1], 2) + Math.pow(a[2], 2) + Math.pow(a[3], 2) + Math.pow(a[4], 2) + Math.pow
(a[5], 2) + 1))
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2d.fromRotation"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>fromRotation (out, rad)](#apidoc.element.gl-matrix.mat2d.fromRotation)
- description and source-code
```javascript
fromRotation = function (out, rad) {
    var s = Math.sin(rad), c = Math.cos(rad);
    out[0] = c;
    out[1] = s;
    out[2] = -s;
    out[3] = c;
    out[4] = 0;
    out[5] = 0;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2d.fromScaling"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>fromScaling (out, v)](#apidoc.element.gl-matrix.mat2d.fromScaling)
- description and source-code
```javascript
fromScaling = function (out, v) {
    out[0] = v[0];
    out[1] = 0;
    out[2] = 0;
    out[3] = v[1];
    out[4] = 0;
    out[5] = 0;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2d.fromTranslation"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>fromTranslation (out, v)](#apidoc.element.gl-matrix.mat2d.fromTranslation)
- description and source-code
```javascript
fromTranslation = function (out, v) {
    out[0] = 1;
    out[1] = 0;
    out[2] = 0;
    out[3] = 1;
    out[4] = v[0];
    out[5] = v[1];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2d.fromValues"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>fromValues (a, b, c, d, tx, ty)](#apidoc.element.gl-matrix.mat2d.fromValues)
- description and source-code
```javascript
fromValues = function (a, b, c, d, tx, ty) {
    var out = new glMatrix.ARRAY_TYPE(6);
    out[0] = a;
    out[1] = b;
    out[2] = c;
    out[3] = d;
    out[4] = tx;
    out[5] = ty;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2d.identity"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>identity (out)](#apidoc.element.gl-matrix.mat2d.identity)
- description and source-code
```javascript
identity = function (out) {
    out[0] = 1;
    out[1] = 0;
    out[2] = 0;
    out[3] = 1;
    out[4] = 0;
    out[5] = 0;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2d.invert"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>invert (out, a)](#apidoc.element.gl-matrix.mat2d.invert)
- description and source-code
```javascript
invert = function (out, a) {
    var aa = a[0], ab = a[1], ac = a[2], ad = a[3],
        atx = a[4], aty = a[5];

    var det = aa * ad - ab * ac;
    if(!det){
        return null;
    }
    det = 1.0 / det;

    out[0] = ad * det;
    out[1] = -ab * det;
    out[2] = -ac * det;
    out[3] = aa * det;
    out[4] = (ac * aty - ad * atx) * det;
    out[5] = (ab * atx - aa * aty) * det;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2d.mul"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>mul (out, a, b)](#apidoc.element.gl-matrix.mat2d.mul)
- description and source-code
```javascript
mul = function (out, a, b) {
    var a0 = a[0], a1 = a[1], a2 = a[2], a3 = a[3], a4 = a[4], a5 = a[5],
        b0 = b[0], b1 = b[1], b2 = b[2], b3 = b[3], b4 = b[4], b5 = b[5];
    out[0] = a0 * b0 + a2 * b1;
    out[1] = a1 * b0 + a3 * b1;
    out[2] = a0 * b2 + a2 * b3;
    out[3] = a1 * b2 + a3 * b3;
    out[4] = a0 * b4 + a2 * b5 + a4;
    out[5] = a1 * b4 + a3 * b5 + a5;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2d.multiply"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>multiply (out, a, b)](#apidoc.element.gl-matrix.mat2d.multiply)
- description and source-code
```javascript
multiply = function (out, a, b) {
    var a0 = a[0], a1 = a[1], a2 = a[2], a3 = a[3], a4 = a[4], a5 = a[5],
        b0 = b[0], b1 = b[1], b2 = b[2], b3 = b[3], b4 = b[4], b5 = b[5];
    out[0] = a0 * b0 + a2 * b1;
    out[1] = a1 * b0 + a3 * b1;
    out[2] = a0 * b2 + a2 * b3;
    out[3] = a1 * b2 + a3 * b3;
    out[4] = a0 * b4 + a2 * b5 + a4;
    out[5] = a1 * b4 + a3 * b5 + a5;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2d.multiplyScalar"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>multiplyScalar (out, a, b)](#apidoc.element.gl-matrix.mat2d.multiplyScalar)
- description and source-code
```javascript
multiplyScalar = function (out, a, b) {
    out[0] = a[0] * b;
    out[1] = a[1] * b;
    out[2] = a[2] * b;
    out[3] = a[3] * b;
    out[4] = a[4] * b;
    out[5] = a[5] * b;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2d.multiplyScalarAndAdd"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>multiplyScalarAndAdd (out, a, b, scale)](#apidoc.element.gl-matrix.mat2d.multiplyScalarAndAdd)
- description and source-code
```javascript
multiplyScalarAndAdd = function (out, a, b, scale) {
    out[0] = a[0] + (b[0] * scale);
    out[1] = a[1] + (b[1] * scale);
    out[2] = a[2] + (b[2] * scale);
    out[3] = a[3] + (b[3] * scale);
    out[4] = a[4] + (b[4] * scale);
    out[5] = a[5] + (b[5] * scale);
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2d.rotate"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>rotate (out, a, rad)](#apidoc.element.gl-matrix.mat2d.rotate)
- description and source-code
```javascript
rotate = function (out, a, rad) {
    var a0 = a[0], a1 = a[1], a2 = a[2], a3 = a[3], a4 = a[4], a5 = a[5],
        s = Math.sin(rad),
        c = Math.cos(rad);
    out[0] = a0 *  c + a2 * s;
    out[1] = a1 *  c + a3 * s;
    out[2] = a0 * -s + a2 * c;
    out[3] = a1 * -s + a3 * c;
    out[4] = a4;
    out[5] = a5;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2d.scale"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>scale (out, a, v)](#apidoc.element.gl-matrix.mat2d.scale)
- description and source-code
```javascript
scale = function (out, a, v) {
    var a0 = a[0], a1 = a[1], a2 = a[2], a3 = a[3], a4 = a[4], a5 = a[5],
        v0 = v[0], v1 = v[1];
    out[0] = a0 * v0;
    out[1] = a1 * v0;
    out[2] = a2 * v1;
    out[3] = a3 * v1;
    out[4] = a4;
    out[5] = a5;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2d.set"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>set (out, a, b, c, d, tx, ty)](#apidoc.element.gl-matrix.mat2d.set)
- description and source-code
```javascript
set = function (out, a, b, c, d, tx, ty) {
    out[0] = a;
    out[1] = b;
    out[2] = c;
    out[3] = d;
    out[4] = tx;
    out[5] = ty;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2d.str"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>str (a)](#apidoc.element.gl-matrix.mat2d.str)
- description and source-code
```javascript
str = function (a) {
    return 'mat2d(' + a[0] + ', ' + a[1] + ', ' + a[2] + ', ' +
                    a[3] + ', ' + a[4] + ', ' + a[5] + ')';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2d.sub"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>sub (out, a, b)](#apidoc.element.gl-matrix.mat2d.sub)
- description and source-code
```javascript
sub = function (out, a, b) {
    out[0] = a[0] - b[0];
    out[1] = a[1] - b[1];
    out[2] = a[2] - b[2];
    out[3] = a[3] - b[3];
    out[4] = a[4] - b[4];
    out[5] = a[5] - b[5];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2d.subtract"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>subtract (out, a, b)](#apidoc.element.gl-matrix.mat2d.subtract)
- description and source-code
```javascript
subtract = function (out, a, b) {
    out[0] = a[0] - b[0];
    out[1] = a[1] - b[1];
    out[2] = a[2] - b[2];
    out[3] = a[3] - b[3];
    out[4] = a[4] - b[4];
    out[5] = a[5] - b[5];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat2d.translate"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat2d.</span>translate (out, a, v)](#apidoc.element.gl-matrix.mat2d.translate)
- description and source-code
```javascript
translate = function (out, a, v) {
    var a0 = a[0], a1 = a[1], a2 = a[2], a3 = a[3], a4 = a[4], a5 = a[5],
        v0 = v[0], v1 = v[1];
    out[0] = a0;
    out[1] = a1;
    out[2] = a2;
    out[3] = a3;
    out[4] = a0 * v0 + a2 * v1 + a4;
    out[5] = a1 * v0 + a3 * v1 + a5;
    return out;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gl-matrix.mat3"></a>[module gl-matrix.mat3](#apidoc.module.gl-matrix.mat3)

#### <a name="apidoc.element.gl-matrix.mat3.add"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>add (out, a, b)](#apidoc.element.gl-matrix.mat3.add)
- description and source-code
```javascript
add = function (out, a, b) {
    out[0] = a[0] + b[0];
    out[1] = a[1] + b[1];
    out[2] = a[2] + b[2];
    out[3] = a[3] + b[3];
    out[4] = a[4] + b[4];
    out[5] = a[5] + b[5];
    out[6] = a[6] + b[6];
    out[7] = a[7] + b[7];
    out[8] = a[8] + b[8];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat3.adjoint"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>adjoint (out, a)](#apidoc.element.gl-matrix.mat3.adjoint)
- description and source-code
```javascript
adjoint = function (out, a) {
    var a00 = a[0], a01 = a[1], a02 = a[2],
        a10 = a[3], a11 = a[4], a12 = a[5],
        a20 = a[6], a21 = a[7], a22 = a[8];

    out[0] = (a11 * a22 - a12 * a21);
    out[1] = (a02 * a21 - a01 * a22);
    out[2] = (a01 * a12 - a02 * a11);
    out[3] = (a12 * a20 - a10 * a22);
    out[4] = (a00 * a22 - a02 * a20);
    out[5] = (a02 * a10 - a00 * a12);
    out[6] = (a10 * a21 - a11 * a20);
    out[7] = (a01 * a20 - a00 * a21);
    out[8] = (a00 * a11 - a01 * a10);
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat3.clone"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>clone (a)](#apidoc.element.gl-matrix.mat3.clone)
- description and source-code
```javascript
clone = function (a) {
    var out = new glMatrix.ARRAY_TYPE(9);
    out[0] = a[0];
    out[1] = a[1];
    out[2] = a[2];
    out[3] = a[3];
    out[4] = a[4];
    out[5] = a[5];
    out[6] = a[6];
    out[7] = a[7];
    out[8] = a[8];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat3.copy"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>copy (out, a)](#apidoc.element.gl-matrix.mat3.copy)
- description and source-code
```javascript
copy = function (out, a) {
    out[0] = a[0];
    out[1] = a[1];
    out[2] = a[2];
    out[3] = a[3];
    out[4] = a[4];
    out[5] = a[5];
    out[6] = a[6];
    out[7] = a[7];
    out[8] = a[8];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat3.create"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>create ()](#apidoc.element.gl-matrix.mat3.create)
- description and source-code
```javascript
create = function () {
    var out = new glMatrix.ARRAY_TYPE(9);
    out[0] = 1;
    out[1] = 0;
    out[2] = 0;
    out[3] = 0;
    out[4] = 1;
    out[5] = 0;
    out[6] = 0;
    out[7] = 0;
    out[8] = 1;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat3.determinant"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>determinant (a)](#apidoc.element.gl-matrix.mat3.determinant)
- description and source-code
```javascript
determinant = function (a) {
    var a00 = a[0], a01 = a[1], a02 = a[2],
        a10 = a[3], a11 = a[4], a12 = a[5],
        a20 = a[6], a21 = a[7], a22 = a[8];

    return a00 * (a22 * a11 - a12 * a21) + a01 * (-a22 * a10 + a12 * a20) + a02 * (a21 * a10 - a11 * a20);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat3.equals"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>equals (a, b)](#apidoc.element.gl-matrix.mat3.equals)
- description and source-code
```javascript
equals = function (a, b) {
    var a0 = a[0], a1 = a[1], a2 = a[2], a3 = a[3], a4 = a[4], a5 = a[5], a6 = a[6], a7 = a[7], a8 = a[8];
    var b0 = b[0], b1 = b[1], b2 = b[2], b3 = b[3], b4 = b[4], b5 = b[5], b6 = a[6], b7 = b[7], b8 = b[8];
    return (Math.abs(a0 - b0) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a0), Math.abs(b0)) &&
            Math.abs(a1 - b1) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a1), Math.abs(b1)) &&
            Math.abs(a2 - b2) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a2), Math.abs(b2)) &&
            Math.abs(a3 - b3) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a3), Math.abs(b3)) &&
            Math.abs(a4 - b4) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a4), Math.abs(b4)) &&
            Math.abs(a5 - b5) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a5), Math.abs(b5)) &&
            Math.abs(a6 - b6) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a6), Math.abs(b6)) &&
            Math.abs(a7 - b7) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a7), Math.abs(b7)) &&
            Math.abs(a8 - b8) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a8), Math.abs(b8)));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat3.exactEquals"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>exactEquals (a, b)](#apidoc.element.gl-matrix.mat3.exactEquals)
- description and source-code
```javascript
exactEquals = function (a, b) {
    return a[0] === b[0] && a[1] === b[1] && a[2] === b[2] &&
           a[3] === b[3] && a[4] === b[4] && a[5] === b[5] &&
           a[6] === b[6] && a[7] === b[7] && a[8] === b[8];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat3.frob"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>frob (a)](#apidoc.element.gl-matrix.mat3.frob)
- description and source-code
```javascript
frob = function (a) {
    return(Math.sqrt(Math.pow(a[0], 2) + Math.pow(a[1], 2) + Math.pow(a[2], 2) + Math.pow(a[3], 2) + Math.pow(a[4], 2) + Math.pow
(a[5], 2) + Math.pow(a[6], 2) + Math.pow(a[7], 2) + Math.pow(a[8], 2)))
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat3.fromMat2d"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>fromMat2d (out, a)](#apidoc.element.gl-matrix.mat3.fromMat2d)
- description and source-code
```javascript
fromMat2d = function (out, a) {
    out[0] = a[0];
    out[1] = a[1];
    out[2] = 0;

    out[3] = a[2];
    out[4] = a[3];
    out[5] = 0;

    out[6] = a[4];
    out[7] = a[5];
    out[8] = 1;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat3.fromMat4"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>fromMat4 (out, a)](#apidoc.element.gl-matrix.mat3.fromMat4)
- description and source-code
```javascript
fromMat4 = function (out, a) {
    out[0] = a[0];
    out[1] = a[1];
    out[2] = a[2];
    out[3] = a[4];
    out[4] = a[5];
    out[5] = a[6];
    out[6] = a[8];
    out[7] = a[9];
    out[8] = a[10];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat3.fromQuat"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>fromQuat (out, q)](#apidoc.element.gl-matrix.mat3.fromQuat)
- description and source-code
```javascript
fromQuat = function (out, q) {
    var x = q[0], y = q[1], z = q[2], w = q[3],
        x2 = x + x,
        y2 = y + y,
        z2 = z + z,

        xx = x * x2,
        yx = y * x2,
        yy = y * y2,
        zx = z * x2,
        zy = z * y2,
        zz = z * z2,
        wx = w * x2,
        wy = w * y2,
        wz = w * z2;

    out[0] = 1 - yy - zz;
    out[3] = yx - wz;
    out[6] = zx + wy;

    out[1] = yx + wz;
    out[4] = 1 - xx - zz;
    out[7] = zy - wx;

    out[2] = zx - wy;
    out[5] = zy + wx;
    out[8] = 1 - xx - yy;

    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat3.fromRotation"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>fromRotation (out, rad)](#apidoc.element.gl-matrix.mat3.fromRotation)
- description and source-code
```javascript
fromRotation = function (out, rad) {
    var s = Math.sin(rad), c = Math.cos(rad);

    out[0] = c;
    out[1] = s;
    out[2] = 0;

    out[3] = -s;
    out[4] = c;
    out[5] = 0;

    out[6] = 0;
    out[7] = 0;
    out[8] = 1;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat3.fromScaling"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>fromScaling (out, v)](#apidoc.element.gl-matrix.mat3.fromScaling)
- description and source-code
```javascript
fromScaling = function (out, v) {
    out[0] = v[0];
    out[1] = 0;
    out[2] = 0;

    out[3] = 0;
    out[4] = v[1];
    out[5] = 0;

    out[6] = 0;
    out[7] = 0;
    out[8] = 1;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat3.fromTranslation"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>fromTranslation (out, v)](#apidoc.element.gl-matrix.mat3.fromTranslation)
- description and source-code
```javascript
fromTranslation = function (out, v) {
    out[0] = 1;
    out[1] = 0;
    out[2] = 0;
    out[3] = 0;
    out[4] = 1;
    out[5] = 0;
    out[6] = v[0];
    out[7] = v[1];
    out[8] = 1;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat3.fromValues"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>fromValues (m00, m01, m02, m10, m11, m12, m20, m21, m22)](#apidoc.element.gl-matrix.mat3.fromValues)
- description and source-code
```javascript
fromValues = function (m00, m01, m02, m10, m11, m12, m20, m21, m22) {
    var out = new glMatrix.ARRAY_TYPE(9);
    out[0] = m00;
    out[1] = m01;
    out[2] = m02;
    out[3] = m10;
    out[4] = m11;
    out[5] = m12;
    out[6] = m20;
    out[7] = m21;
    out[8] = m22;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat3.identity"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>identity (out)](#apidoc.element.gl-matrix.mat3.identity)
- description and source-code
```javascript
identity = function (out) {
    out[0] = 1;
    out[1] = 0;
    out[2] = 0;
    out[3] = 0;
    out[4] = 1;
    out[5] = 0;
    out[6] = 0;
    out[7] = 0;
    out[8] = 1;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat3.invert"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>invert (out, a)](#apidoc.element.gl-matrix.mat3.invert)
- description and source-code
```javascript
invert = function (out, a) {
    var a00 = a[0], a01 = a[1], a02 = a[2],
        a10 = a[3], a11 = a[4], a12 = a[5],
        a20 = a[6], a21 = a[7], a22 = a[8],

        b01 = a22 * a11 - a12 * a21,
        b11 = -a22 * a10 + a12 * a20,
        b21 = a21 * a10 - a11 * a20,

        // Calculate the determinant
        det = a00 * b01 + a01 * b11 + a02 * b21;

    if (!det) {
        return null;
    }
    det = 1.0 / det;

    out[0] = b01 * det;
    out[1] = (-a22 * a01 + a02 * a21) * det;
    out[2] = (a12 * a01 - a02 * a11) * det;
    out[3] = b11 * det;
    out[4] = (a22 * a00 - a02 * a20) * det;
    out[5] = (-a12 * a00 + a02 * a10) * det;
    out[6] = b21 * det;
    out[7] = (-a21 * a00 + a01 * a20) * det;
    out[8] = (a11 * a00 - a01 * a10) * det;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat3.mul"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>mul (out, a, b)](#apidoc.element.gl-matrix.mat3.mul)
- description and source-code
```javascript
mul = function (out, a, b) {
    var a00 = a[0], a01 = a[1], a02 = a[2],
        a10 = a[3], a11 = a[4], a12 = a[5],
        a20 = a[6], a21 = a[7], a22 = a[8],

        b00 = b[0], b01 = b[1], b02 = b[2],
        b10 = b[3], b11 = b[4], b12 = b[5],
        b20 = b[6], b21 = b[7], b22 = b[8];

    out[0] = b00 * a00 + b01 * a10 + b02 * a20;
    out[1] = b00 * a01 + b01 * a11 + b02 * a21;
    out[2] = b00 * a02 + b01 * a12 + b02 * a22;

    out[3] = b10 * a00 + b11 * a10 + b12 * a20;
    out[4] = b10 * a01 + b11 * a11 + b12 * a21;
    out[5] = b10 * a02 + b11 * a12 + b12 * a22;

    out[6] = b20 * a00 + b21 * a10 + b22 * a20;
    out[7] = b20 * a01 + b21 * a11 + b22 * a21;
    out[8] = b20 * a02 + b21 * a12 + b22 * a22;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat3.multiply"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>multiply (out, a, b)](#apidoc.element.gl-matrix.mat3.multiply)
- description and source-code
```javascript
multiply = function (out, a, b) {
    var a00 = a[0], a01 = a[1], a02 = a[2],
        a10 = a[3], a11 = a[4], a12 = a[5],
        a20 = a[6], a21 = a[7], a22 = a[8],

        b00 = b[0], b01 = b[1], b02 = b[2],
        b10 = b[3], b11 = b[4], b12 = b[5],
        b20 = b[6], b21 = b[7], b22 = b[8];

    out[0] = b00 * a00 + b01 * a10 + b02 * a20;
    out[1] = b00 * a01 + b01 * a11 + b02 * a21;
    out[2] = b00 * a02 + b01 * a12 + b02 * a22;

    out[3] = b10 * a00 + b11 * a10 + b12 * a20;
    out[4] = b10 * a01 + b11 * a11 + b12 * a21;
    out[5] = b10 * a02 + b11 * a12 + b12 * a22;

    out[6] = b20 * a00 + b21 * a10 + b22 * a20;
    out[7] = b20 * a01 + b21 * a11 + b22 * a21;
    out[8] = b20 * a02 + b21 * a12 + b22 * a22;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat3.multiplyScalar"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>multiplyScalar (out, a, b)](#apidoc.element.gl-matrix.mat3.multiplyScalar)
- description and source-code
```javascript
multiplyScalar = function (out, a, b) {
    out[0] = a[0] * b;
    out[1] = a[1] * b;
    out[2] = a[2] * b;
    out[3] = a[3] * b;
    out[4] = a[4] * b;
    out[5] = a[5] * b;
    out[6] = a[6] * b;
    out[7] = a[7] * b;
    out[8] = a[8] * b;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat3.multiplyScalarAndAdd"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>multiplyScalarAndAdd (out, a, b, scale)](#apidoc.element.gl-matrix.mat3.multiplyScalarAndAdd)
- description and source-code
```javascript
multiplyScalarAndAdd = function (out, a, b, scale) {
    out[0] = a[0] + (b[0] * scale);
    out[1] = a[1] + (b[1] * scale);
    out[2] = a[2] + (b[2] * scale);
    out[3] = a[3] + (b[3] * scale);
    out[4] = a[4] + (b[4] * scale);
    out[5] = a[5] + (b[5] * scale);
    out[6] = a[6] + (b[6] * scale);
    out[7] = a[7] + (b[7] * scale);
    out[8] = a[8] + (b[8] * scale);
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat3.normalFromMat4"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>normalFromMat4 (out, a)](#apidoc.element.gl-matrix.mat3.normalFromMat4)
- description and source-code
```javascript
normalFromMat4 = function (out, a) {
    var a00 = a[0], a01 = a[1], a02 = a[2], a03 = a[3],
        a10 = a[4], a11 = a[5], a12 = a[6], a13 = a[7],
        a20 = a[8], a21 = a[9], a22 = a[10], a23 = a[11],
        a30 = a[12], a31 = a[13], a32 = a[14], a33 = a[15],

        b00 = a00 * a11 - a01 * a10,
        b01 = a00 * a12 - a02 * a10,
        b02 = a00 * a13 - a03 * a10,
        b03 = a01 * a12 - a02 * a11,
        b04 = a01 * a13 - a03 * a11,
        b05 = a02 * a13 - a03 * a12,
        b06 = a20 * a31 - a21 * a30,
        b07 = a20 * a32 - a22 * a30,
        b08 = a20 * a33 - a23 * a30,
        b09 = a21 * a32 - a22 * a31,
        b10 = a21 * a33 - a23 * a31,
        b11 = a22 * a33 - a23 * a32,

        // Calculate the determinant
        det = b00 * b11 - b01 * b10 + b02 * b09 + b03 * b08 - b04 * b07 + b05 * b06;

    if (!det) {
        return null;
    }
    det = 1.0 / det;

    out[0] = (a11 * b11 - a12 * b10 + a13 * b09) * det;
    out[1] = (a12 * b08 - a10 * b11 - a13 * b07) * det;
    out[2] = (a10 * b10 - a11 * b08 + a13 * b06) * det;

    out[3] = (a02 * b10 - a01 * b11 - a03 * b09) * det;
    out[4] = (a00 * b11 - a02 * b08 + a03 * b07) * det;
    out[5] = (a01 * b08 - a00 * b10 - a03 * b06) * det;

    out[6] = (a31 * b05 - a32 * b04 + a33 * b03) * det;
    out[7] = (a32 * b02 - a30 * b05 - a33 * b01) * det;
    out[8] = (a30 * b04 - a31 * b02 + a33 * b00) * det;

    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat3.rotate"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>rotate (out, a, rad)](#apidoc.element.gl-matrix.mat3.rotate)
- description and source-code
```javascript
rotate = function (out, a, rad) {
    var a00 = a[0], a01 = a[1], a02 = a[2],
        a10 = a[3], a11 = a[4], a12 = a[5],
        a20 = a[6], a21 = a[7], a22 = a[8],

        s = Math.sin(rad),
        c = Math.cos(rad);

    out[0] = c * a00 + s * a10;
    out[1] = c * a01 + s * a11;
    out[2] = c * a02 + s * a12;

    out[3] = c * a10 - s * a00;
    out[4] = c * a11 - s * a01;
    out[5] = c * a12 - s * a02;

    out[6] = a20;
    out[7] = a21;
    out[8] = a22;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat3.scale"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>scale (out, a, v)](#apidoc.element.gl-matrix.mat3.scale)
- description and source-code
```javascript
scale = function (out, a, v) {
    var x = v[0], y = v[1];

    out[0] = x * a[0];
    out[1] = x * a[1];
    out[2] = x * a[2];

    out[3] = y * a[3];
    out[4] = y * a[4];
    out[5] = y * a[5];

    out[6] = a[6];
    out[7] = a[7];
    out[8] = a[8];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat3.set"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>set (out, m00, m01, m02, m10, m11, m12, m20, m21, m22)](#apidoc.element.gl-matrix.mat3.set)
- description and source-code
```javascript
set = function (out, m00, m01, m02, m10, m11, m12, m20, m21, m22) {
    out[0] = m00;
    out[1] = m01;
    out[2] = m02;
    out[3] = m10;
    out[4] = m11;
    out[5] = m12;
    out[6] = m20;
    out[7] = m21;
    out[8] = m22;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat3.str"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>str (a)](#apidoc.element.gl-matrix.mat3.str)
- description and source-code
```javascript
str = function (a) {
    return 'mat3(' + a[0] + ', ' + a[1] + ', ' + a[2] + ', ' +
                    a[3] + ', ' + a[4] + ', ' + a[5] + ', ' +
                    a[6] + ', ' + a[7] + ', ' + a[8] + ')';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat3.sub"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>sub (out, a, b)](#apidoc.element.gl-matrix.mat3.sub)
- description and source-code
```javascript
sub = function (out, a, b) {
    out[0] = a[0] - b[0];
    out[1] = a[1] - b[1];
    out[2] = a[2] - b[2];
    out[3] = a[3] - b[3];
    out[4] = a[4] - b[4];
    out[5] = a[5] - b[5];
    out[6] = a[6] - b[6];
    out[7] = a[7] - b[7];
    out[8] = a[8] - b[8];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat3.subtract"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>subtract (out, a, b)](#apidoc.element.gl-matrix.mat3.subtract)
- description and source-code
```javascript
subtract = function (out, a, b) {
    out[0] = a[0] - b[0];
    out[1] = a[1] - b[1];
    out[2] = a[2] - b[2];
    out[3] = a[3] - b[3];
    out[4] = a[4] - b[4];
    out[5] = a[5] - b[5];
    out[6] = a[6] - b[6];
    out[7] = a[7] - b[7];
    out[8] = a[8] - b[8];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat3.translate"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>translate (out, a, v)](#apidoc.element.gl-matrix.mat3.translate)
- description and source-code
```javascript
translate = function (out, a, v) {
    var a00 = a[0], a01 = a[1], a02 = a[2],
        a10 = a[3], a11 = a[4], a12 = a[5],
        a20 = a[6], a21 = a[7], a22 = a[8],
        x = v[0], y = v[1];

    out[0] = a00;
    out[1] = a01;
    out[2] = a02;

    out[3] = a10;
    out[4] = a11;
    out[5] = a12;

    out[6] = x * a00 + y * a10 + a20;
    out[7] = x * a01 + y * a11 + a21;
    out[8] = x * a02 + y * a12 + a22;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat3.transpose"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat3.</span>transpose (out, a)](#apidoc.element.gl-matrix.mat3.transpose)
- description and source-code
```javascript
transpose = function (out, a) {
    // If we are transposing ourselves we can skip a few steps but have to cache some values
    if (out === a) {
        var a01 = a[1], a02 = a[2], a12 = a[5];
        out[1] = a[3];
        out[2] = a[6];
        out[3] = a01;
        out[5] = a[7];
        out[6] = a02;
        out[7] = a12;
    } else {
        out[0] = a[0];
        out[1] = a[3];
        out[2] = a[6];
        out[3] = a[1];
        out[4] = a[4];
        out[5] = a[7];
        out[6] = a[2];
        out[7] = a[5];
        out[8] = a[8];
    }

    return out;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gl-matrix.mat4"></a>[module gl-matrix.mat4](#apidoc.module.gl-matrix.mat4)

#### <a name="apidoc.element.gl-matrix.mat4.add"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>add (out, a, b)](#apidoc.element.gl-matrix.mat4.add)
- description and source-code
```javascript
add = function (out, a, b) {
    out[0] = a[0] + b[0];
    out[1] = a[1] + b[1];
    out[2] = a[2] + b[2];
    out[3] = a[3] + b[3];
    out[4] = a[4] + b[4];
    out[5] = a[5] + b[5];
    out[6] = a[6] + b[6];
    out[7] = a[7] + b[7];
    out[8] = a[8] + b[8];
    out[9] = a[9] + b[9];
    out[10] = a[10] + b[10];
    out[11] = a[11] + b[11];
    out[12] = a[12] + b[12];
    out[13] = a[13] + b[13];
    out[14] = a[14] + b[14];
    out[15] = a[15] + b[15];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.adjoint"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>adjoint (out, a)](#apidoc.element.gl-matrix.mat4.adjoint)
- description and source-code
```javascript
adjoint = function (out, a) {
    var a00 = a[0], a01 = a[1], a02 = a[2], a03 = a[3],
        a10 = a[4], a11 = a[5], a12 = a[6], a13 = a[7],
        a20 = a[8], a21 = a[9], a22 = a[10], a23 = a[11],
        a30 = a[12], a31 = a[13], a32 = a[14], a33 = a[15];

    out[0]  =  (a11 * (a22 * a33 - a23 * a32) - a21 * (a12 * a33 - a13 * a32) + a31 * (a12 * a23 - a13 * a22));
    out[1]  = -(a01 * (a22 * a33 - a23 * a32) - a21 * (a02 * a33 - a03 * a32) + a31 * (a02 * a23 - a03 * a22));
    out[2]  =  (a01 * (a12 * a33 - a13 * a32) - a11 * (a02 * a33 - a03 * a32) + a31 * (a02 * a13 - a03 * a12));
    out[3]  = -(a01 * (a12 * a23 - a13 * a22) - a11 * (a02 * a23 - a03 * a22) + a21 * (a02 * a13 - a03 * a12));
    out[4]  = -(a10 * (a22 * a33 - a23 * a32) - a20 * (a12 * a33 - a13 * a32) + a30 * (a12 * a23 - a13 * a22));
    out[5]  =  (a00 * (a22 * a33 - a23 * a32) - a20 * (a02 * a33 - a03 * a32) + a30 * (a02 * a23 - a03 * a22));
    out[6]  = -(a00 * (a12 * a33 - a13 * a32) - a10 * (a02 * a33 - a03 * a32) + a30 * (a02 * a13 - a03 * a12));
    out[7]  =  (a00 * (a12 * a23 - a13 * a22) - a10 * (a02 * a23 - a03 * a22) + a20 * (a02 * a13 - a03 * a12));
    out[8]  =  (a10 * (a21 * a33 - a23 * a31) - a20 * (a11 * a33 - a13 * a31) + a30 * (a11 * a23 - a13 * a21));
    out[9]  = -(a00 * (a21 * a33 - a23 * a31) - a20 * (a01 * a33 - a03 * a31) + a30 * (a01 * a23 - a03 * a21));
    out[10] =  (a00 * (a11 * a33 - a13 * a31) - a10 * (a01 * a33 - a03 * a31) + a30 * (a01 * a13 - a03 * a11));
    out[11] = -(a00 * (a11 * a23 - a13 * a21) - a10 * (a01 * a23 - a03 * a21) + a20 * (a01 * a13 - a03 * a11));
    out[12] = -(a10 * (a21 * a32 - a22 * a31) - a20 * (a11 * a32 - a12 * a31) + a30 * (a11 * a22 - a12 * a21));
    out[13] =  (a00 * (a21 * a32 - a22 * a31) - a20 * (a01 * a32 - a02 * a31) + a30 * (a01 * a22 - a02 * a21));
    out[14] = -(a00 * (a11 * a32 - a12 * a31) - a10 * (a01 * a32 - a02 * a31) + a30 * (a01 * a12 - a02 * a11));
    out[15] =  (a00 * (a11 * a22 - a12 * a21) - a10 * (a01 * a22 - a02 * a21) + a20 * (a01 * a12 - a02 * a11));
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.clone"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>clone (a)](#apidoc.element.gl-matrix.mat4.clone)
- description and source-code
```javascript
clone = function (a) {
    var out = new glMatrix.ARRAY_TYPE(16);
    out[0] = a[0];
    out[1] = a[1];
    out[2] = a[2];
    out[3] = a[3];
    out[4] = a[4];
    out[5] = a[5];
    out[6] = a[6];
    out[7] = a[7];
    out[8] = a[8];
    out[9] = a[9];
    out[10] = a[10];
    out[11] = a[11];
    out[12] = a[12];
    out[13] = a[13];
    out[14] = a[14];
    out[15] = a[15];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.copy"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>copy (out, a)](#apidoc.element.gl-matrix.mat4.copy)
- description and source-code
```javascript
copy = function (out, a) {
    out[0] = a[0];
    out[1] = a[1];
    out[2] = a[2];
    out[3] = a[3];
    out[4] = a[4];
    out[5] = a[5];
    out[6] = a[6];
    out[7] = a[7];
    out[8] = a[8];
    out[9] = a[9];
    out[10] = a[10];
    out[11] = a[11];
    out[12] = a[12];
    out[13] = a[13];
    out[14] = a[14];
    out[15] = a[15];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.create"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>create ()](#apidoc.element.gl-matrix.mat4.create)
- description and source-code
```javascript
create = function () {
    var out = new glMatrix.ARRAY_TYPE(16);
    out[0] = 1;
    out[1] = 0;
    out[2] = 0;
    out[3] = 0;
    out[4] = 0;
    out[5] = 1;
    out[6] = 0;
    out[7] = 0;
    out[8] = 0;
    out[9] = 0;
    out[10] = 1;
    out[11] = 0;
    out[12] = 0;
    out[13] = 0;
    out[14] = 0;
    out[15] = 1;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.determinant"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>determinant (a)](#apidoc.element.gl-matrix.mat4.determinant)
- description and source-code
```javascript
determinant = function (a) {
    var a00 = a[0], a01 = a[1], a02 = a[2], a03 = a[3],
        a10 = a[4], a11 = a[5], a12 = a[6], a13 = a[7],
        a20 = a[8], a21 = a[9], a22 = a[10], a23 = a[11],
        a30 = a[12], a31 = a[13], a32 = a[14], a33 = a[15],

        b00 = a00 * a11 - a01 * a10,
        b01 = a00 * a12 - a02 * a10,
        b02 = a00 * a13 - a03 * a10,
        b03 = a01 * a12 - a02 * a11,
        b04 = a01 * a13 - a03 * a11,
        b05 = a02 * a13 - a03 * a12,
        b06 = a20 * a31 - a21 * a30,
        b07 = a20 * a32 - a22 * a30,
        b08 = a20 * a33 - a23 * a30,
        b09 = a21 * a32 - a22 * a31,
        b10 = a21 * a33 - a23 * a31,
        b11 = a22 * a33 - a23 * a32;

    // Calculate the determinant
    return b00 * b11 - b01 * b10 + b02 * b09 + b03 * b08 - b04 * b07 + b05 * b06;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.equals"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>equals (a, b)](#apidoc.element.gl-matrix.mat4.equals)
- description and source-code
```javascript
equals = function (a, b) {
    var a0  = a[0],  a1  = a[1],  a2  = a[2],  a3  = a[3],
        a4  = a[4],  a5  = a[5],  a6  = a[6],  a7  = a[7],
        a8  = a[8],  a9  = a[9],  a10 = a[10], a11 = a[11],
        a12 = a[12], a13 = a[13], a14 = a[14], a15 = a[15];

    var b0  = b[0],  b1  = b[1],  b2  = b[2],  b3  = b[3],
        b4  = b[4],  b5  = b[5],  b6  = b[6],  b7  = b[7],
        b8  = b[8],  b9  = b[9],  b10 = b[10], b11 = b[11],
        b12 = b[12], b13 = b[13], b14 = b[14], b15 = b[15];

    return (Math.abs(a0 - b0) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a0), Math.abs(b0)) &&
            Math.abs(a1 - b1) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a1), Math.abs(b1)) &&
            Math.abs(a2 - b2) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a2), Math.abs(b2)) &&
            Math.abs(a3 - b3) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a3), Math.abs(b3)) &&
            Math.abs(a4 - b4) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a4), Math.abs(b4)) &&
            Math.abs(a5 - b5) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a5), Math.abs(b5)) &&
            Math.abs(a6 - b6) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a6), Math.abs(b6)) &&
            Math.abs(a7 - b7) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a7), Math.abs(b7)) &&
            Math.abs(a8 - b8) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a8), Math.abs(b8)) &&
            Math.abs(a9 - b9) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a9), Math.abs(b9)) &&
            Math.abs(a10 - b10) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a10), Math.abs(b10)) &&
            Math.abs(a11 - b11) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a11), Math.abs(b11)) &&
            Math.abs(a12 - b12) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a12), Math.abs(b12)) &&
            Math.abs(a13 - b13) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a13), Math.abs(b13)) &&
            Math.abs(a14 - b14) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a14), Math.abs(b14)) &&
            Math.abs(a15 - b15) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a15), Math.abs(b15)));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.exactEquals"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>exactEquals (a, b)](#apidoc.element.gl-matrix.mat4.exactEquals)
- description and source-code
```javascript
exactEquals = function (a, b) {
    return a[0] === b[0] && a[1] === b[1] && a[2] === b[2] && a[3] === b[3] &&
           a[4] === b[4] && a[5] === b[5] && a[6] === b[6] && a[7] === b[7] &&
           a[8] === b[8] && a[9] === b[9] && a[10] === b[10] && a[11] === b[11] &&
           a[12] === b[12] && a[13] === b[13] && a[14] === b[14] && a[15] === b[15];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.frob"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>frob (a)](#apidoc.element.gl-matrix.mat4.frob)
- description and source-code
```javascript
frob = function (a) {
    return(Math.sqrt(Math.pow(a[0], 2) + Math.pow(a[1], 2) + Math.pow(a[2], 2) + Math.pow(a[3], 2) + Math.pow(a[4], 2) + Math.pow
(a[5], 2) + Math.pow(a[6], 2) + Math.pow(a[7], 2) + Math.pow(a[8], 2) + Math.pow(a[9], 2) + Math.pow(a[10], 2) + Math.pow(a[11],
2) + Math.pow(a[12], 2) + Math.pow(a[13], 2) + Math.pow(a[14], 2) + Math.pow(a[15], 2) ))
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.fromQuat"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>fromQuat (out, q)](#apidoc.element.gl-matrix.mat4.fromQuat)
- description and source-code
```javascript
fromQuat = function (out, q) {
    var x = q[0], y = q[1], z = q[2], w = q[3],
        x2 = x + x,
        y2 = y + y,
        z2 = z + z,

        xx = x * x2,
        yx = y * x2,
        yy = y * y2,
        zx = z * x2,
        zy = z * y2,
        zz = z * z2,
        wx = w * x2,
        wy = w * y2,
        wz = w * z2;

    out[0] = 1 - yy - zz;
    out[1] = yx + wz;
    out[2] = zx - wy;
    out[3] = 0;

    out[4] = yx - wz;
    out[5] = 1 - xx - zz;
    out[6] = zy + wx;
    out[7] = 0;

    out[8] = zx + wy;
    out[9] = zy - wx;
    out[10] = 1 - xx - yy;
    out[11] = 0;

    out[12] = 0;
    out[13] = 0;
    out[14] = 0;
    out[15] = 1;

    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.fromRotation"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>fromRotation (out, rad, axis)](#apidoc.element.gl-matrix.mat4.fromRotation)
- description and source-code
```javascript
fromRotation = function (out, rad, axis) {
    var x = axis[0], y = axis[1], z = axis[2],
        len = Math.sqrt(x * x + y * y + z * z),
        s, c, t;

    if (Math.abs(len) < glMatrix.EPSILON) { return null; }

    len = 1 / len;
    x *= len;
    y *= len;
    z *= len;

    s = Math.sin(rad);
    c = Math.cos(rad);
    t = 1 - c;

    // Perform rotation-specific matrix multiplication
    out[0] = x * x * t + c;
    out[1] = y * x * t + z * s;
    out[2] = z * x * t - y * s;
    out[3] = 0;
    out[4] = x * y * t - z * s;
    out[5] = y * y * t + c;
    out[6] = z * y * t + x * s;
    out[7] = 0;
    out[8] = x * z * t + y * s;
    out[9] = y * z * t - x * s;
    out[10] = z * z * t + c;
    out[11] = 0;
    out[12] = 0;
    out[13] = 0;
    out[14] = 0;
    out[15] = 1;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.fromRotationTranslation"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>fromRotationTranslation (out, q, v)](#apidoc.element.gl-matrix.mat4.fromRotationTranslation)
- description and source-code
```javascript
fromRotationTranslation = function (out, q, v) {
    // Quaternion math
    var x = q[0], y = q[1], z = q[2], w = q[3],
        x2 = x + x,
        y2 = y + y,
        z2 = z + z,

        xx = x * x2,
        xy = x * y2,
        xz = x * z2,
        yy = y * y2,
        yz = y * z2,
        zz = z * z2,
        wx = w * x2,
        wy = w * y2,
        wz = w * z2;

    out[0] = 1 - (yy + zz);
    out[1] = xy + wz;
    out[2] = xz - wy;
    out[3] = 0;
    out[4] = xy - wz;
    out[5] = 1 - (xx + zz);
    out[6] = yz + wx;
    out[7] = 0;
    out[8] = xz + wy;
    out[9] = yz - wx;
    out[10] = 1 - (xx + yy);
    out[11] = 0;
    out[12] = v[0];
    out[13] = v[1];
    out[14] = v[2];
    out[15] = 1;

    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.fromRotationTranslationScale"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>fromRotationTranslationScale (out, q, v, s)](#apidoc.element.gl-matrix.mat4.fromRotationTranslationScale)
- description and source-code
```javascript
fromRotationTranslationScale = function (out, q, v, s) {
    // Quaternion math
    var x = q[0], y = q[1], z = q[2], w = q[3],
        x2 = x + x,
        y2 = y + y,
        z2 = z + z,

        xx = x * x2,
        xy = x * y2,
        xz = x * z2,
        yy = y * y2,
        yz = y * z2,
        zz = z * z2,
        wx = w * x2,
        wy = w * y2,
        wz = w * z2,
        sx = s[0],
        sy = s[1],
        sz = s[2];

    out[0] = (1 - (yy + zz)) * sx;
    out[1] = (xy + wz) * sx;
    out[2] = (xz - wy) * sx;
    out[3] = 0;
    out[4] = (xy - wz) * sy;
    out[5] = (1 - (xx + zz)) * sy;
    out[6] = (yz + wx) * sy;
    out[7] = 0;
    out[8] = (xz + wy) * sz;
    out[9] = (yz - wx) * sz;
    out[10] = (1 - (xx + yy)) * sz;
    out[11] = 0;
    out[12] = v[0];
    out[13] = v[1];
    out[14] = v[2];
    out[15] = 1;

    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.fromRotationTranslationScaleOrigin"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>fromRotationTranslationScaleOrigin (out, q, v, s, o)](#apidoc.element.gl-matrix.mat4.fromRotationTranslationScaleOrigin)
- description and source-code
```javascript
fromRotationTranslationScaleOrigin = function (out, q, v, s, o) {
  // Quaternion math
  var x = q[0], y = q[1], z = q[2], w = q[3],
      x2 = x + x,
      y2 = y + y,
      z2 = z + z,

      xx = x * x2,
      xy = x * y2,
      xz = x * z2,
      yy = y * y2,
      yz = y * z2,
      zz = z * z2,
      wx = w * x2,
      wy = w * y2,
      wz = w * z2,

      sx = s[0],
      sy = s[1],
      sz = s[2],

      ox = o[0],
      oy = o[1],
      oz = o[2];

  out[0] = (1 - (yy + zz)) * sx;
  out[1] = (xy + wz) * sx;
  out[2] = (xz - wy) * sx;
  out[3] = 0;
  out[4] = (xy - wz) * sy;
  out[5] = (1 - (xx + zz)) * sy;
  out[6] = (yz + wx) * sy;
  out[7] = 0;
  out[8] = (xz + wy) * sz;
  out[9] = (yz - wx) * sz;
  out[10] = (1 - (xx + yy)) * sz;
  out[11] = 0;
  out[12] = v[0] + ox - (out[0] * ox + out[4] * oy + out[8] * oz);
  out[13] = v[1] + oy - (out[1] * ox + out[5] * oy + out[9] * oz);
  out[14] = v[2] + oz - (out[2] * ox + out[6] * oy + out[10] * oz);
  out[15] = 1;

  return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.fromScaling"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>fromScaling (out, v)](#apidoc.element.gl-matrix.mat4.fromScaling)
- description and source-code
```javascript
fromScaling = function (out, v) {
    out[0] = v[0];
    out[1] = 0;
    out[2] = 0;
    out[3] = 0;
    out[4] = 0;
    out[5] = v[1];
    out[6] = 0;
    out[7] = 0;
    out[8] = 0;
    out[9] = 0;
    out[10] = v[2];
    out[11] = 0;
    out[12] = 0;
    out[13] = 0;
    out[14] = 0;
    out[15] = 1;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.fromTranslation"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>fromTranslation (out, v)](#apidoc.element.gl-matrix.mat4.fromTranslation)
- description and source-code
```javascript
fromTranslation = function (out, v) {
    out[0] = 1;
    out[1] = 0;
    out[2] = 0;
    out[3] = 0;
    out[4] = 0;
    out[5] = 1;
    out[6] = 0;
    out[7] = 0;
    out[8] = 0;
    out[9] = 0;
    out[10] = 1;
    out[11] = 0;
    out[12] = v[0];
    out[13] = v[1];
    out[14] = v[2];
    out[15] = 1;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.fromValues"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>fromValues (m00, m01, m02, m03, m10, m11, m12, m13, m20, m21, m22, m23, m30, m31, m32, m33)](#apidoc.element.gl-matrix.mat4.fromValues)
- description and source-code
```javascript
fromValues = function (m00, m01, m02, m03, m10, m11, m12, m13, m20, m21, m22, m23, m30, m31, m32, m33) {
    var out = new glMatrix.ARRAY_TYPE(16);
    out[0] = m00;
    out[1] = m01;
    out[2] = m02;
    out[3] = m03;
    out[4] = m10;
    out[5] = m11;
    out[6] = m12;
    out[7] = m13;
    out[8] = m20;
    out[9] = m21;
    out[10] = m22;
    out[11] = m23;
    out[12] = m30;
    out[13] = m31;
    out[14] = m32;
    out[15] = m33;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.fromXRotation"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>fromXRotation (out, rad)](#apidoc.element.gl-matrix.mat4.fromXRotation)
- description and source-code
```javascript
fromXRotation = function (out, rad) {
    var s = Math.sin(rad),
        c = Math.cos(rad);

    // Perform axis-specific matrix multiplication
    out[0]  = 1;
    out[1]  = 0;
    out[2]  = 0;
    out[3]  = 0;
    out[4] = 0;
    out[5] = c;
    out[6] = s;
    out[7] = 0;
    out[8] = 0;
    out[9] = -s;
    out[10] = c;
    out[11] = 0;
    out[12] = 0;
    out[13] = 0;
    out[14] = 0;
    out[15] = 1;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.fromYRotation"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>fromYRotation (out, rad)](#apidoc.element.gl-matrix.mat4.fromYRotation)
- description and source-code
```javascript
fromYRotation = function (out, rad) {
    var s = Math.sin(rad),
        c = Math.cos(rad);

    // Perform axis-specific matrix multiplication
    out[0]  = c;
    out[1]  = 0;
    out[2]  = -s;
    out[3]  = 0;
    out[4] = 0;
    out[5] = 1;
    out[6] = 0;
    out[7] = 0;
    out[8] = s;
    out[9] = 0;
    out[10] = c;
    out[11] = 0;
    out[12] = 0;
    out[13] = 0;
    out[14] = 0;
    out[15] = 1;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.fromZRotation"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>fromZRotation (out, rad)](#apidoc.element.gl-matrix.mat4.fromZRotation)
- description and source-code
```javascript
fromZRotation = function (out, rad) {
    var s = Math.sin(rad),
        c = Math.cos(rad);

    // Perform axis-specific matrix multiplication
    out[0]  = c;
    out[1]  = s;
    out[2]  = 0;
    out[3]  = 0;
    out[4] = -s;
    out[5] = c;
    out[6] = 0;
    out[7] = 0;
    out[8] = 0;
    out[9] = 0;
    out[10] = 1;
    out[11] = 0;
    out[12] = 0;
    out[13] = 0;
    out[14] = 0;
    out[15] = 1;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.frustum"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>frustum (out, left, right, bottom, top, near, far)](#apidoc.element.gl-matrix.mat4.frustum)
- description and source-code
```javascript
frustum = function (out, left, right, bottom, top, near, far) {
    var rl = 1 / (right - left),
        tb = 1 / (top - bottom),
        nf = 1 / (near - far);
    out[0] = (near * 2) * rl;
    out[1] = 0;
    out[2] = 0;
    out[3] = 0;
    out[4] = 0;
    out[5] = (near * 2) * tb;
    out[6] = 0;
    out[7] = 0;
    out[8] = (right + left) * rl;
    out[9] = (top + bottom) * tb;
    out[10] = (far + near) * nf;
    out[11] = -1;
    out[12] = 0;
    out[13] = 0;
    out[14] = (far * near * 2) * nf;
    out[15] = 0;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.getRotation"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>getRotation (out, mat)](#apidoc.element.gl-matrix.mat4.getRotation)
- description and source-code
```javascript
getRotation = function (out, mat) {
  // Algorithm taken from http://www.euclideanspace.com/maths/geometry/rotations/conversions/matrixToQuaternion/index.htm
  var trace = mat[0] + mat[5] + mat[10];
  var S = 0;

  if (trace > 0) {
    S = Math.sqrt(trace + 1.0) * 2;
    out[3] = 0.25 * S;
    out[0] = (mat[6] - mat[9]) / S;
    out[1] = (mat[8] - mat[2]) / S;
    out[2] = (mat[1] - mat[4]) / S;
  } else if ((mat[0] > mat[5])&(mat[0] > mat[10])) {
    S = Math.sqrt(1.0 + mat[0] - mat[5] - mat[10]) * 2;
    out[3] = (mat[6] - mat[9]) / S;
    out[0] = 0.25 * S;
    out[1] = (mat[1] + mat[4]) / S;
    out[2] = (mat[8] + mat[2]) / S;
  } else if (mat[5] > mat[10]) {
    S = Math.sqrt(1.0 + mat[5] - mat[0] - mat[10]) * 2;
    out[3] = (mat[8] - mat[2]) / S;
    out[0] = (mat[1] + mat[4]) / S;
    out[1] = 0.25 * S;
    out[2] = (mat[6] + mat[9]) / S;
  } else {
    S = Math.sqrt(1.0 + mat[10] - mat[0] - mat[5]) * 2;
    out[3] = (mat[1] - mat[4]) / S;
    out[0] = (mat[8] + mat[2]) / S;
    out[1] = (mat[6] + mat[9]) / S;
    out[2] = 0.25 * S;
  }

  return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.getTranslation"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>getTranslation (out, mat)](#apidoc.element.gl-matrix.mat4.getTranslation)
- description and source-code
```javascript
getTranslation = function (out, mat) {
  out[0] = mat[12];
  out[1] = mat[13];
  out[2] = mat[14];

  return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.identity"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>identity (out)](#apidoc.element.gl-matrix.mat4.identity)
- description and source-code
```javascript
identity = function (out) {
    out[0] = 1;
    out[1] = 0;
    out[2] = 0;
    out[3] = 0;
    out[4] = 0;
    out[5] = 1;
    out[6] = 0;
    out[7] = 0;
    out[8] = 0;
    out[9] = 0;
    out[10] = 1;
    out[11] = 0;
    out[12] = 0;
    out[13] = 0;
    out[14] = 0;
    out[15] = 1;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.invert"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>invert (out, a)](#apidoc.element.gl-matrix.mat4.invert)
- description and source-code
```javascript
invert = function (out, a) {
    var a00 = a[0], a01 = a[1], a02 = a[2], a03 = a[3],
        a10 = a[4], a11 = a[5], a12 = a[6], a13 = a[7],
        a20 = a[8], a21 = a[9], a22 = a[10], a23 = a[11],
        a30 = a[12], a31 = a[13], a32 = a[14], a33 = a[15],

        b00 = a00 * a11 - a01 * a10,
        b01 = a00 * a12 - a02 * a10,
        b02 = a00 * a13 - a03 * a10,
        b03 = a01 * a12 - a02 * a11,
        b04 = a01 * a13 - a03 * a11,
        b05 = a02 * a13 - a03 * a12,
        b06 = a20 * a31 - a21 * a30,
        b07 = a20 * a32 - a22 * a30,
        b08 = a20 * a33 - a23 * a30,
        b09 = a21 * a32 - a22 * a31,
        b10 = a21 * a33 - a23 * a31,
        b11 = a22 * a33 - a23 * a32,

        // Calculate the determinant
        det = b00 * b11 - b01 * b10 + b02 * b09 + b03 * b08 - b04 * b07 + b05 * b06;

    if (!det) {
        return null;
    }
    det = 1.0 / det;

    out[0] = (a11 * b11 - a12 * b10 + a13 * b09) * det;
    out[1] = (a02 * b10 - a01 * b11 - a03 * b09) * det;
    out[2] = (a31 * b05 - a32 * b04 + a33 * b03) * det;
    out[3] = (a22 * b04 - a21 * b05 - a23 * b03) * det;
    out[4] = (a12 * b08 - a10 * b11 - a13 * b07) * det;
    out[5] = (a00 * b11 - a02 * b08 + a03 * b07) * det;
    out[6] = (a32 * b02 - a30 * b05 - a33 * b01) * det;
    out[7] = (a20 * b05 - a22 * b02 + a23 * b01) * det;
    out[8] = (a10 * b10 - a11 * b08 + a13 * b06) * det;
    out[9] = (a01 * b08 - a00 * b10 - a03 * b06) * det;
    out[10] = (a30 * b04 - a31 * b02 + a33 * b00) * det;
    out[11] = (a21 * b02 - a20 * b04 - a23 * b00) * det;
    out[12] = (a11 * b07 - a10 * b09 - a12 * b06) * det;
    out[13] = (a00 * b09 - a01 * b07 + a02 * b06) * det;
    out[14] = (a31 * b01 - a30 * b03 - a32 * b00) * det;
    out[15] = (a20 * b03 - a21 * b01 + a22 * b00) * det;

    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.lookAt"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>lookAt (out, eye, center, up)](#apidoc.element.gl-matrix.mat4.lookAt)
- description and source-code
```javascript
lookAt = function (out, eye, center, up) {
    var x0, x1, x2, y0, y1, y2, z0, z1, z2, len,
        eyex = eye[0],
        eyey = eye[1],
        eyez = eye[2],
        upx = up[0],
        upy = up[1],
        upz = up[2],
        centerx = center[0],
        centery = center[1],
        centerz = center[2];

    if (Math.abs(eyex - centerx) < glMatrix.EPSILON &&
        Math.abs(eyey - centery) < glMatrix.EPSILON &&
        Math.abs(eyez - centerz) < glMatrix.EPSILON) {
        return mat4.identity(out);
    }

    z0 = eyex - centerx;
    z1 = eyey - centery;
    z2 = eyez - centerz;

    len = 1 / Math.sqrt(z0 * z0 + z1 * z1 + z2 * z2);
    z0 *= len;
    z1 *= len;
    z2 *= len;

    x0 = upy * z2 - upz * z1;
    x1 = upz * z0 - upx * z2;
    x2 = upx * z1 - upy * z0;
    len = Math.sqrt(x0 * x0 + x1 * x1 + x2 * x2);
    if (!len) {
        x0 = 0;
        x1 = 0;
        x2 = 0;
    } else {
        len = 1 / len;
        x0 *= len;
        x1 *= len;
        x2 *= len;
    }

    y0 = z1 * x2 - z2 * x1;
    y1 = z2 * x0 - z0 * x2;
    y2 = z0 * x1 - z1 * x0;

    len = Math.sqrt(y0 * y0 + y1 * y1 + y2 * y2);
    if (!len) {
        y0 = 0;
        y1 = 0;
        y2 = 0;
    } else {
        len = 1 / len;
        y0 *= len;
        y1 *= len;
        y2 *= len;
    }

    out[0] = x0;
    out[1] = y0;
    out[2] = z0;
    out[3] = 0;
    out[4] = x1;
    out[5] = y1;
    out[6] = z1;
    out[7] = 0;
    out[8] = x2;
    out[9] = y2;
    out[10] = z2;
    out[11] = 0;
    out[12] = -(x0 * eyex + x1 * eyey + x2 * eyez);
    out[13] = -(y0 * eyex + y1 * eyey + y2 * eyez);
    out[14] = -(z0 * eyex + z1 * eyey + z2 * eyez);
    out[15] = 1;

    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.mul"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>mul (out, a, b)](#apidoc.element.gl-matrix.mat4.mul)
- description and source-code
```javascript
mul = function (out, a, b) {
    var a00 = a[0], a01 = a[1], a02 = a[2], a03 = a[3],
        a10 = a[4], a11 = a[5], a12 = a[6], a13 = a[7],
        a20 = a[8], a21 = a[9], a22 = a[10], a23 = a[11],
        a30 = a[12], a31 = a[13], a32 = a[14], a33 = a[15];

    // Cache only the current line of the second matrix
    var b0  = b[0], b1 = b[1], b2 = b[2], b3 = b[3];
    out[0] = b0*a00 + b1*a10 + b2*a20 + b3*a30;
    out[1] = b0*a01 + b1*a11 + b2*a21 + b3*a31;
    out[2] = b0*a02 + b1*a12 + b2*a22 + b3*a32;
    out[3] = b0*a03 + b1*a13 + b2*a23 + b3*a33;

    b0 = b[4]; b1 = b[5]; b2 = b[6]; b3 = b[7];
    out[4] = b0*a00 + b1*a10 + b2*a20 + b3*a30;
    out[5] = b0*a01 + b1*a11 + b2*a21 + b3*a31;
    out[6] = b0*a02 + b1*a12 + b2*a22 + b3*a32;
    out[7] = b0*a03 + b1*a13 + b2*a23 + b3*a33;

    b0 = b[8]; b1 = b[9]; b2 = b[10]; b3 = b[11];
    out[8] = b0*a00 + b1*a10 + b2*a20 + b3*a30;
    out[9] = b0*a01 + b1*a11 + b2*a21 + b3*a31;
    out[10] = b0*a02 + b1*a12 + b2*a22 + b3*a32;
    out[11] = b0*a03 + b1*a13 + b2*a23 + b3*a33;

    b0 = b[12]; b1 = b[13]; b2 = b[14]; b3 = b[15];
    out[12] = b0*a00 + b1*a10 + b2*a20 + b3*a30;
    out[13] = b0*a01 + b1*a11 + b2*a21 + b3*a31;
    out[14] = b0*a02 + b1*a12 + b2*a22 + b3*a32;
    out[15] = b0*a03 + b1*a13 + b2*a23 + b3*a33;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.multiply"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>multiply (out, a, b)](#apidoc.element.gl-matrix.mat4.multiply)
- description and source-code
```javascript
multiply = function (out, a, b) {
    var a00 = a[0], a01 = a[1], a02 = a[2], a03 = a[3],
        a10 = a[4], a11 = a[5], a12 = a[6], a13 = a[7],
        a20 = a[8], a21 = a[9], a22 = a[10], a23 = a[11],
        a30 = a[12], a31 = a[13], a32 = a[14], a33 = a[15];

    // Cache only the current line of the second matrix
    var b0  = b[0], b1 = b[1], b2 = b[2], b3 = b[3];
    out[0] = b0*a00 + b1*a10 + b2*a20 + b3*a30;
    out[1] = b0*a01 + b1*a11 + b2*a21 + b3*a31;
    out[2] = b0*a02 + b1*a12 + b2*a22 + b3*a32;
    out[3] = b0*a03 + b1*a13 + b2*a23 + b3*a33;

    b0 = b[4]; b1 = b[5]; b2 = b[6]; b3 = b[7];
    out[4] = b0*a00 + b1*a10 + b2*a20 + b3*a30;
    out[5] = b0*a01 + b1*a11 + b2*a21 + b3*a31;
    out[6] = b0*a02 + b1*a12 + b2*a22 + b3*a32;
    out[7] = b0*a03 + b1*a13 + b2*a23 + b3*a33;

    b0 = b[8]; b1 = b[9]; b2 = b[10]; b3 = b[11];
    out[8] = b0*a00 + b1*a10 + b2*a20 + b3*a30;
    out[9] = b0*a01 + b1*a11 + b2*a21 + b3*a31;
    out[10] = b0*a02 + b1*a12 + b2*a22 + b3*a32;
    out[11] = b0*a03 + b1*a13 + b2*a23 + b3*a33;

    b0 = b[12]; b1 = b[13]; b2 = b[14]; b3 = b[15];
    out[12] = b0*a00 + b1*a10 + b2*a20 + b3*a30;
    out[13] = b0*a01 + b1*a11 + b2*a21 + b3*a31;
    out[14] = b0*a02 + b1*a12 + b2*a22 + b3*a32;
    out[15] = b0*a03 + b1*a13 + b2*a23 + b3*a33;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.multiplyScalar"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>multiplyScalar (out, a, b)](#apidoc.element.gl-matrix.mat4.multiplyScalar)
- description and source-code
```javascript
multiplyScalar = function (out, a, b) {
    out[0] = a[0] * b;
    out[1] = a[1] * b;
    out[2] = a[2] * b;
    out[3] = a[3] * b;
    out[4] = a[4] * b;
    out[5] = a[5] * b;
    out[6] = a[6] * b;
    out[7] = a[7] * b;
    out[8] = a[8] * b;
    out[9] = a[9] * b;
    out[10] = a[10] * b;
    out[11] = a[11] * b;
    out[12] = a[12] * b;
    out[13] = a[13] * b;
    out[14] = a[14] * b;
    out[15] = a[15] * b;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.multiplyScalarAndAdd"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>multiplyScalarAndAdd (out, a, b, scale)](#apidoc.element.gl-matrix.mat4.multiplyScalarAndAdd)
- description and source-code
```javascript
multiplyScalarAndAdd = function (out, a, b, scale) {
    out[0] = a[0] + (b[0] * scale);
    out[1] = a[1] + (b[1] * scale);
    out[2] = a[2] + (b[2] * scale);
    out[3] = a[3] + (b[3] * scale);
    out[4] = a[4] + (b[4] * scale);
    out[5] = a[5] + (b[5] * scale);
    out[6] = a[6] + (b[6] * scale);
    out[7] = a[7] + (b[7] * scale);
    out[8] = a[8] + (b[8] * scale);
    out[9] = a[9] + (b[9] * scale);
    out[10] = a[10] + (b[10] * scale);
    out[11] = a[11] + (b[11] * scale);
    out[12] = a[12] + (b[12] * scale);
    out[13] = a[13] + (b[13] * scale);
    out[14] = a[14] + (b[14] * scale);
    out[15] = a[15] + (b[15] * scale);
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.ortho"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>ortho (out, left, right, bottom, top, near, far)](#apidoc.element.gl-matrix.mat4.ortho)
- description and source-code
```javascript
ortho = function (out, left, right, bottom, top, near, far) {
    var lr = 1 / (left - right),
        bt = 1 / (bottom - top),
        nf = 1 / (near - far);
    out[0] = -2 * lr;
    out[1] = 0;
    out[2] = 0;
    out[3] = 0;
    out[4] = 0;
    out[5] = -2 * bt;
    out[6] = 0;
    out[7] = 0;
    out[8] = 0;
    out[9] = 0;
    out[10] = 2 * nf;
    out[11] = 0;
    out[12] = (left + right) * lr;
    out[13] = (top + bottom) * bt;
    out[14] = (far + near) * nf;
    out[15] = 1;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.perspective"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>perspective (out, fovy, aspect, near, far)](#apidoc.element.gl-matrix.mat4.perspective)
- description and source-code
```javascript
perspective = function (out, fovy, aspect, near, far) {
    var f = 1.0 / Math.tan(fovy / 2),
        nf = 1 / (near - far);
    out[0] = f / aspect;
    out[1] = 0;
    out[2] = 0;
    out[3] = 0;
    out[4] = 0;
    out[5] = f;
    out[6] = 0;
    out[7] = 0;
    out[8] = 0;
    out[9] = 0;
    out[10] = (far + near) * nf;
    out[11] = -1;
    out[12] = 0;
    out[13] = 0;
    out[14] = (2 * far * near) * nf;
    out[15] = 0;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.perspectiveFromFieldOfView"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>perspectiveFromFieldOfView (out, fov, near, far)](#apidoc.element.gl-matrix.mat4.perspectiveFromFieldOfView)
- description and source-code
```javascript
perspectiveFromFieldOfView = function (out, fov, near, far) {
    var upTan = Math.tan(fov.upDegrees * Math.PI/180.0),
        downTan = Math.tan(fov.downDegrees * Math.PI/180.0),
        leftTan = Math.tan(fov.leftDegrees * Math.PI/180.0),
        rightTan = Math.tan(fov.rightDegrees * Math.PI/180.0),
        xScale = 2.0 / (leftTan + rightTan),
        yScale = 2.0 / (upTan + downTan);

    out[0] = xScale;
    out[1] = 0.0;
    out[2] = 0.0;
    out[3] = 0.0;
    out[4] = 0.0;
    out[5] = yScale;
    out[6] = 0.0;
    out[7] = 0.0;
    out[8] = -((leftTan - rightTan) * xScale * 0.5);
    out[9] = ((upTan - downTan) * yScale * 0.5);
    out[10] = far / (near - far);
    out[11] = -1.0;
    out[12] = 0.0;
    out[13] = 0.0;
    out[14] = (far * near) / (near - far);
    out[15] = 0.0;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.rotate"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>rotate (out, a, rad, axis)](#apidoc.element.gl-matrix.mat4.rotate)
- description and source-code
```javascript
rotate = function (out, a, rad, axis) {
    var x = axis[0], y = axis[1], z = axis[2],
        len = Math.sqrt(x * x + y * y + z * z),
        s, c, t,
        a00, a01, a02, a03,
        a10, a11, a12, a13,
        a20, a21, a22, a23,
        b00, b01, b02,
        b10, b11, b12,
        b20, b21, b22;

    if (Math.abs(len) < glMatrix.EPSILON) { return null; }

    len = 1 / len;
    x *= len;
    y *= len;
    z *= len;

    s = Math.sin(rad);
    c = Math.cos(rad);
    t = 1 - c;

    a00 = a[0]; a01 = a[1]; a02 = a[2]; a03 = a[3];
    a10 = a[4]; a11 = a[5]; a12 = a[6]; a13 = a[7];
    a20 = a[8]; a21 = a[9]; a22 = a[10]; a23 = a[11];

    // Construct the elements of the rotation matrix
    b00 = x * x * t + c; b01 = y * x * t + z * s; b02 = z * x * t - y * s;
    b10 = x * y * t - z * s; b11 = y * y * t + c; b12 = z * y * t + x * s;
    b20 = x * z * t + y * s; b21 = y * z * t - x * s; b22 = z * z * t + c;

    // Perform rotation-specific matrix multiplication
    out[0] = a00 * b00 + a10 * b01 + a20 * b02;
    out[1] = a01 * b00 + a11 * b01 + a21 * b02;
    out[2] = a02 * b00 + a12 * b01 + a22 * b02;
    out[3] = a03 * b00 + a13 * b01 + a23 * b02;
    out[4] = a00 * b10 + a10 * b11 + a20 * b12;
    out[5] = a01 * b10 + a11 * b11 + a21 * b12;
    out[6] = a02 * b10 + a12 * b11 + a22 * b12;
    out[7] = a03 * b10 + a13 * b11 + a23 * b12;
    out[8] = a00 * b20 + a10 * b21 + a20 * b22;
    out[9] = a01 * b20 + a11 * b21 + a21 * b22;
    out[10] = a02 * b20 + a12 * b21 + a22 * b22;
    out[11] = a03 * b20 + a13 * b21 + a23 * b22;

    if (a !== out) { // If the source and destination differ, copy the unchanged last row
        out[12] = a[12];
        out[13] = a[13];
        out[14] = a[14];
        out[15] = a[15];
    }
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.rotateX"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>rotateX (out, a, rad)](#apidoc.element.gl-matrix.mat4.rotateX)
- description and source-code
```javascript
rotateX = function (out, a, rad) {
    var s = Math.sin(rad),
        c = Math.cos(rad),
        a10 = a[4],
        a11 = a[5],
        a12 = a[6],
        a13 = a[7],
        a20 = a[8],
        a21 = a[9],
        a22 = a[10],
        a23 = a[11];

    if (a !== out) { // If the source and destination differ, copy the unchanged rows
        out[0]  = a[0];
        out[1]  = a[1];
        out[2]  = a[2];
        out[3]  = a[3];
        out[12] = a[12];
        out[13] = a[13];
        out[14] = a[14];
        out[15] = a[15];
    }

    // Perform axis-specific matrix multiplication
    out[4] = a10 * c + a20 * s;
    out[5] = a11 * c + a21 * s;
    out[6] = a12 * c + a22 * s;
    out[7] = a13 * c + a23 * s;
    out[8] = a20 * c - a10 * s;
    out[9] = a21 * c - a11 * s;
    out[10] = a22 * c - a12 * s;
    out[11] = a23 * c - a13 * s;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.rotateY"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>rotateY (out, a, rad)](#apidoc.element.gl-matrix.mat4.rotateY)
- description and source-code
```javascript
rotateY = function (out, a, rad) {
    var s = Math.sin(rad),
        c = Math.cos(rad),
        a00 = a[0],
        a01 = a[1],
        a02 = a[2],
        a03 = a[3],
        a20 = a[8],
        a21 = a[9],
        a22 = a[10],
        a23 = a[11];

    if (a !== out) { // If the source and destination differ, copy the unchanged rows
        out[4]  = a[4];
        out[5]  = a[5];
        out[6]  = a[6];
        out[7]  = a[7];
        out[12] = a[12];
        out[13] = a[13];
        out[14] = a[14];
        out[15] = a[15];
    }

    // Perform axis-specific matrix multiplication
    out[0] = a00 * c - a20 * s;
    out[1] = a01 * c - a21 * s;
    out[2] = a02 * c - a22 * s;
    out[3] = a03 * c - a23 * s;
    out[8] = a00 * s + a20 * c;
    out[9] = a01 * s + a21 * c;
    out[10] = a02 * s + a22 * c;
    out[11] = a03 * s + a23 * c;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.rotateZ"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>rotateZ (out, a, rad)](#apidoc.element.gl-matrix.mat4.rotateZ)
- description and source-code
```javascript
rotateZ = function (out, a, rad) {
    var s = Math.sin(rad),
        c = Math.cos(rad),
        a00 = a[0],
        a01 = a[1],
        a02 = a[2],
        a03 = a[3],
        a10 = a[4],
        a11 = a[5],
        a12 = a[6],
        a13 = a[7];

    if (a !== out) { // If the source and destination differ, copy the unchanged last row
        out[8]  = a[8];
        out[9]  = a[9];
        out[10] = a[10];
        out[11] = a[11];
        out[12] = a[12];
        out[13] = a[13];
        out[14] = a[14];
        out[15] = a[15];
    }

    // Perform axis-specific matrix multiplication
    out[0] = a00 * c + a10 * s;
    out[1] = a01 * c + a11 * s;
    out[2] = a02 * c + a12 * s;
    out[3] = a03 * c + a13 * s;
    out[4] = a10 * c - a00 * s;
    out[5] = a11 * c - a01 * s;
    out[6] = a12 * c - a02 * s;
    out[7] = a13 * c - a03 * s;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.scale"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>scale (out, a, v)](#apidoc.element.gl-matrix.mat4.scale)
- description and source-code
```javascript
scale = function (out, a, v) {
    var x = v[0], y = v[1], z = v[2];

    out[0] = a[0] * x;
    out[1] = a[1] * x;
    out[2] = a[2] * x;
    out[3] = a[3] * x;
    out[4] = a[4] * y;
    out[5] = a[5] * y;
    out[6] = a[6] * y;
    out[7] = a[7] * y;
    out[8] = a[8] * z;
    out[9] = a[9] * z;
    out[10] = a[10] * z;
    out[11] = a[11] * z;
    out[12] = a[12];
    out[13] = a[13];
    out[14] = a[14];
    out[15] = a[15];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.set"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>set (out, m00, m01, m02, m03, m10, m11, m12, m13, m20, m21, m22, m23, m30, m31, m32, m33)](#apidoc.element.gl-matrix.mat4.set)
- description and source-code
```javascript
set = function (out, m00, m01, m02, m03, m10, m11, m12, m13, m20, m21, m22, m23, m30, m31, m32, m33) {
    out[0] = m00;
    out[1] = m01;
    out[2] = m02;
    out[3] = m03;
    out[4] = m10;
    out[5] = m11;
    out[6] = m12;
    out[7] = m13;
    out[8] = m20;
    out[9] = m21;
    out[10] = m22;
    out[11] = m23;
    out[12] = m30;
    out[13] = m31;
    out[14] = m32;
    out[15] = m33;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.str"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>str (a)](#apidoc.element.gl-matrix.mat4.str)
- description and source-code
```javascript
str = function (a) {
    return 'mat4(' + a[0] + ', ' + a[1] + ', ' + a[2] + ', ' + a[3] + ', ' +
                    a[4] + ', ' + a[5] + ', ' + a[6] + ', ' + a[7] + ', ' +
                    a[8] + ', ' + a[9] + ', ' + a[10] + ', ' + a[11] + ', ' +
                    a[12] + ', ' + a[13] + ', ' + a[14] + ', ' + a[15] + ')';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.sub"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>sub (out, a, b)](#apidoc.element.gl-matrix.mat4.sub)
- description and source-code
```javascript
sub = function (out, a, b) {
    out[0] = a[0] - b[0];
    out[1] = a[1] - b[1];
    out[2] = a[2] - b[2];
    out[3] = a[3] - b[3];
    out[4] = a[4] - b[4];
    out[5] = a[5] - b[5];
    out[6] = a[6] - b[6];
    out[7] = a[7] - b[7];
    out[8] = a[8] - b[8];
    out[9] = a[9] - b[9];
    out[10] = a[10] - b[10];
    out[11] = a[11] - b[11];
    out[12] = a[12] - b[12];
    out[13] = a[13] - b[13];
    out[14] = a[14] - b[14];
    out[15] = a[15] - b[15];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.subtract"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>subtract (out, a, b)](#apidoc.element.gl-matrix.mat4.subtract)
- description and source-code
```javascript
subtract = function (out, a, b) {
    out[0] = a[0] - b[0];
    out[1] = a[1] - b[1];
    out[2] = a[2] - b[2];
    out[3] = a[3] - b[3];
    out[4] = a[4] - b[4];
    out[5] = a[5] - b[5];
    out[6] = a[6] - b[6];
    out[7] = a[7] - b[7];
    out[8] = a[8] - b[8];
    out[9] = a[9] - b[9];
    out[10] = a[10] - b[10];
    out[11] = a[11] - b[11];
    out[12] = a[12] - b[12];
    out[13] = a[13] - b[13];
    out[14] = a[14] - b[14];
    out[15] = a[15] - b[15];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.translate"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>translate (out, a, v)](#apidoc.element.gl-matrix.mat4.translate)
- description and source-code
```javascript
translate = function (out, a, v) {
    var x = v[0], y = v[1], z = v[2],
        a00, a01, a02, a03,
        a10, a11, a12, a13,
        a20, a21, a22, a23;

    if (a === out) {
        out[12] = a[0] * x + a[4] * y + a[8] * z + a[12];
        out[13] = a[1] * x + a[5] * y + a[9] * z + a[13];
        out[14] = a[2] * x + a[6] * y + a[10] * z + a[14];
        out[15] = a[3] * x + a[7] * y + a[11] * z + a[15];
    } else {
        a00 = a[0]; a01 = a[1]; a02 = a[2]; a03 = a[3];
        a10 = a[4]; a11 = a[5]; a12 = a[6]; a13 = a[7];
        a20 = a[8]; a21 = a[9]; a22 = a[10]; a23 = a[11];

        out[0] = a00; out[1] = a01; out[2] = a02; out[3] = a03;
        out[4] = a10; out[5] = a11; out[6] = a12; out[7] = a13;
        out[8] = a20; out[9] = a21; out[10] = a22; out[11] = a23;

        out[12] = a00 * x + a10 * y + a20 * z + a[12];
        out[13] = a01 * x + a11 * y + a21 * z + a[13];
        out[14] = a02 * x + a12 * y + a22 * z + a[14];
        out[15] = a03 * x + a13 * y + a23 * z + a[15];
    }

    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.transpose"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.</span>transpose (out, a)](#apidoc.element.gl-matrix.mat4.transpose)
- description and source-code
```javascript
transpose = function (out, a) {
    // If we are transposing ourselves we can skip a few steps but have to cache some values
    if (out === a) {
        var a01 = a[1], a02 = a[2], a03 = a[3],
            a12 = a[6], a13 = a[7],
            a23 = a[11];

        out[1] = a[4];
        out[2] = a[8];
        out[3] = a[12];
        out[4] = a01;
        out[6] = a[9];
        out[7] = a[13];
        out[8] = a02;
        out[9] = a12;
        out[11] = a[14];
        out[12] = a03;
        out[13] = a13;
        out[14] = a23;
    } else {
        out[0] = a[0];
        out[1] = a[4];
        out[2] = a[8];
        out[3] = a[12];
        out[4] = a[1];
        out[5] = a[5];
        out[6] = a[9];
        out[7] = a[13];
        out[8] = a[2];
        out[9] = a[6];
        out[10] = a[10];
        out[11] = a[14];
        out[12] = a[3];
        out[13] = a[7];
        out[14] = a[11];
        out[15] = a[15];
    }

    return out;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gl-matrix.mat4.SIMD"></a>[module gl-matrix.mat4.SIMD](#apidoc.module.gl-matrix.mat4.SIMD)

#### <a name="apidoc.element.gl-matrix.mat4.SIMD.adjoint"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.SIMD.</span>adjoint (out, a)](#apidoc.element.gl-matrix.mat4.SIMD.adjoint)
- description and source-code
```javascript
adjoint = function (out, a) {
  var a0, a1, a2, a3;
  var row0, row1, row2, row3;
  var tmp1;
  var minor0, minor1, minor2, minor3;

  var a0 = SIMD.Float32x4.load(a, 0);
  var a1 = SIMD.Float32x4.load(a, 4);
  var a2 = SIMD.Float32x4.load(a, 8);
  var a3 = SIMD.Float32x4.load(a, 12);

  // Transpose the source matrix.  Sort of.  Not a true transpose operation
  tmp1 = SIMD.Float32x4.shuffle(a0, a1, 0, 1, 4, 5);
  row1 = SIMD.Float32x4.shuffle(a2, a3, 0, 1, 4, 5);
  row0 = SIMD.Float32x4.shuffle(tmp1, row1, 0, 2, 4, 6);
  row1 = SIMD.Float32x4.shuffle(row1, tmp1, 1, 3, 5, 7);

  tmp1 = SIMD.Float32x4.shuffle(a0, a1, 2, 3, 6, 7);
  row3 = SIMD.Float32x4.shuffle(a2, a3, 2, 3, 6, 7);
  row2 = SIMD.Float32x4.shuffle(tmp1, row3, 0, 2, 4, 6);
  row3 = SIMD.Float32x4.shuffle(row3, tmp1, 1, 3, 5, 7);

  tmp1   = SIMD.Float32x4.mul(row2, row3);
  tmp1   = SIMD.Float32x4.swizzle(tmp1, 1, 0, 3, 2);
  minor0 = SIMD.Float32x4.mul(row1, tmp1);
  minor1 = SIMD.Float32x4.mul(row0, tmp1);
  tmp1   = SIMD.Float32x4.swizzle(tmp1, 2, 3, 0, 1);
  minor0 = SIMD.Float32x4.sub(SIMD.Float32x4.mul(row1, tmp1), minor0);
  minor1 = SIMD.Float32x4.sub(SIMD.Float32x4.mul(row0, tmp1), minor1);
  minor1 = SIMD.Float32x4.swizzle(minor1, 2, 3, 0, 1);

  tmp1   = SIMD.Float32x4.mul(row1, row2);
  tmp1   = SIMD.Float32x4.swizzle(tmp1, 1, 0, 3, 2);
  minor0 = SIMD.Float32x4.add(SIMD.Float32x4.mul(row3, tmp1), minor0);
  minor3 = SIMD.Float32x4.mul(row0, tmp1);
  tmp1   = SIMD.Float32x4.swizzle(tmp1, 2, 3, 0, 1);
  minor0 = SIMD.Float32x4.sub(minor0, SIMD.Float32x4.mul(row3, tmp1));
  minor3 = SIMD.Float32x4.sub(SIMD.Float32x4.mul(row0, tmp1), minor3);
  minor3 = SIMD.Float32x4.swizzle(minor3, 2, 3, 0, 1);

  tmp1   = SIMD.Float32x4.mul(SIMD.Float32x4.swizzle(row1, 2, 3, 0, 1), row3);
  tmp1   = SIMD.Float32x4.swizzle(tmp1, 1, 0, 3, 2);
  row2   = SIMD.Float32x4.swizzle(row2, 2, 3, 0, 1);
  minor0 = SIMD.Float32x4.add(SIMD.Float32x4.mul(row2, tmp1), minor0);
  minor2 = SIMD.Float32x4.mul(row0, tmp1);
  tmp1   = SIMD.Float32x4.swizzle(tmp1, 2, 3, 0, 1);
  minor0 = SIMD.Float32x4.sub(minor0, SIMD.Float32x4.mul(row2, tmp1));
  minor2 = SIMD.Float32x4.sub(SIMD.Float32x4.mul(row0, tmp1), minor2);
  minor2 = SIMD.Float32x4.swizzle(minor2, 2, 3, 0, 1);

  tmp1   = SIMD.Float32x4.mul(row0, row1);
  tmp1   = SIMD.Float32x4.swizzle(tmp1, 1, 0, 3, 2);
  minor2 = SIMD.Float32x4.add(SIMD.Float32x4.mul(row3, tmp1), minor2);
  minor3 = SIMD.Float32x4.sub(SIMD.Float32x4.mul(row2, tmp1), minor3);
  tmp1   = SIMD.Float32x4.swizzle(tmp1, 2, 3, 0, 1);
  minor2 = SIMD.Float32x4.sub(SIMD.Float32x4.mul(row3, tmp1), minor2);
  minor3 = SIMD.Float32x4.sub(minor3, SIMD.Float32x4.mul(row2, tmp1));

  tmp1   = SIMD.Float32x4.mul(row0, row3);
  tmp1   = SIMD.Float32x4.swizzle(tmp1, 1, 0, 3, 2);
  minor1 = SIMD.Float32x4.sub(minor1, SIMD.Float32x4.mul(row2, tmp1));
  minor2 = SIMD.Float32x4.add(SIMD.Float32x4.mul(row1, tmp1), minor2);
  tmp1   = SIMD.Float32x4.swizzle(tmp1, 2, 3, 0, 1);
  minor1 = SIMD.Float32x4.add(SIMD.Float32x4.mul(row2, tmp1), minor1);
  minor2 = SIMD.Float32x4.sub(minor2, SIMD.Float32x4.mul(row1, tmp1));

  tmp1   = SIMD.Float32x4.mul(row0, row2);
  tmp1   = SIMD.Float32x4.swizzle(tmp1, 1, 0, 3, 2);
  minor1 = SIMD.Float32x4.add(SIMD.Float32x4.mul(row3, tmp1), minor1);
  minor3 = SIMD.Float32x4.sub(minor3, SIMD.Float32x4.mul(row1, tmp1));
  tmp1   = SIMD.Float32x4.swizzle(tmp1, 2, 3, 0, 1);
  minor1 = SIMD.Float32x4.sub(minor1, SIMD.Float32x4.mul(row3, tmp1));
  minor3 = SIMD.Float32x4.add(SIMD.Float32x4.mul(row1, tmp1), minor3);

  SIMD.Float32x4.store(out, 0,  minor0);
  SIMD.Float32x4.store(out, 4,  minor1);
  SIMD.Float32x4.store(out, 8,  minor2);
  SIMD.Float32x4.store(out, 12, minor3);
  return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.SIMD.invert"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.SIMD.</span>invert (out, a)](#apidoc.element.gl-matrix.mat4.SIMD.invert)
- description and source-code
```javascript
invert = function (out, a) {
  var row0, row1, row2, row3,
      tmp1,
      minor0, minor1, minor2, minor3,
      det,
      a0 = SIMD.Float32x4.load(a, 0),
      a1 = SIMD.Float32x4.load(a, 4),
      a2 = SIMD.Float32x4.load(a, 8),
      a3 = SIMD.Float32x4.load(a, 12);

  // Compute matrix adjugate
  tmp1 = SIMD.Float32x4.shuffle(a0, a1, 0, 1, 4, 5);
  row1 = SIMD.Float32x4.shuffle(a2, a3, 0, 1, 4, 5);
  row0 = SIMD.Float32x4.shuffle(tmp1, row1, 0, 2, 4, 6);
  row1 = SIMD.Float32x4.shuffle(row1, tmp1, 1, 3, 5, 7);
  tmp1 = SIMD.Float32x4.shuffle(a0, a1, 2, 3, 6, 7);
  row3 = SIMD.Float32x4.shuffle(a2, a3, 2, 3, 6, 7);
  row2 = SIMD.Float32x4.shuffle(tmp1, row3, 0, 2, 4, 6);
  row3 = SIMD.Float32x4.shuffle(row3, tmp1, 1, 3, 5, 7);

  tmp1   = SIMD.Float32x4.mul(row2, row3);
  tmp1   = SIMD.Float32x4.swizzle(tmp1, 1, 0, 3, 2);
  minor0 = SIMD.Float32x4.mul(row1, tmp1);
  minor1 = SIMD.Float32x4.mul(row0, tmp1);
  tmp1   = SIMD.Float32x4.swizzle(tmp1, 2, 3, 0, 1);
  minor0 = SIMD.Float32x4.sub(SIMD.Float32x4.mul(row1, tmp1), minor0);
  minor1 = SIMD.Float32x4.sub(SIMD.Float32x4.mul(row0, tmp1), minor1);
  minor1 = SIMD.Float32x4.swizzle(minor1, 2, 3, 0, 1);

  tmp1   = SIMD.Float32x4.mul(row1, row2);
  tmp1   = SIMD.Float32x4.swizzle(tmp1, 1, 0, 3, 2);
  minor0 = SIMD.Float32x4.add(SIMD.Float32x4.mul(row3, tmp1), minor0);
  minor3 = SIMD.Float32x4.mul(row0, tmp1);
  tmp1   = SIMD.Float32x4.swizzle(tmp1, 2, 3, 0, 1);
  minor0 = SIMD.Float32x4.sub(minor0, SIMD.Float32x4.mul(row3, tmp1));
  minor3 = SIMD.Float32x4.sub(SIMD.Float32x4.mul(row0, tmp1), minor3);
  minor3 = SIMD.Float32x4.swizzle(minor3, 2, 3, 0, 1);

  tmp1   = SIMD.Float32x4.mul(SIMD.Float32x4.swizzle(row1, 2, 3, 0, 1), row3);
  tmp1   = SIMD.Float32x4.swizzle(tmp1, 1, 0, 3, 2);
  row2   = SIMD.Float32x4.swizzle(row2, 2, 3, 0, 1);
  minor0 = SIMD.Float32x4.add(SIMD.Float32x4.mul(row2, tmp1), minor0);
  minor2 = SIMD.Float32x4.mul(row0, tmp1);
  tmp1   = SIMD.Float32x4.swizzle(tmp1, 2, 3, 0, 1);
  minor0 = SIMD.Float32x4.sub(minor0, SIMD.Float32x4.mul(row2, tmp1));
  minor2 = SIMD.Float32x4.sub(SIMD.Float32x4.mul(row0, tmp1), minor2);
  minor2 = SIMD.Float32x4.swizzle(minor2, 2, 3, 0, 1);

  tmp1   = SIMD.Float32x4.mul(row0, row1);
  tmp1   = SIMD.Float32x4.swizzle(tmp1, 1, 0, 3, 2);
  minor2 = SIMD.Float32x4.add(SIMD.Float32x4.mul(row3, tmp1), minor2);
  minor3 = SIMD.Float32x4.sub(SIMD.Float32x4.mul(row2, tmp1), minor3);
  tmp1   = SIMD.Float32x4.swizzle(tmp1, 2, 3, 0, 1);
  minor2 = SIMD.Float32x4.sub(SIMD.Float32x4.mul(row3, tmp1), minor2);
  minor3 = SIMD.Float32x4.sub(minor3, SIMD.Float32x4.mul(row2, tmp1));

  tmp1   = SIMD.Float32x4.mul(row0, row3);
  tmp1   = SIMD.Float32x4.swizzle(tmp1, 1, 0, 3, 2);
  minor1 = SIMD.Float32x4.sub(minor1, SIMD.Float32x4.mul(row2, tmp1));
  minor2 = SIMD.Float32x4.add(SIMD.Float32x4.mul(row1, tmp1), minor2);
  tmp1   = SIMD.Float32x4.swizzle(tmp1, 2, 3, 0, 1);
  minor1 = SIMD.Float32x4.add(SIMD.Float32x4.mul(row2, tmp1), minor1);
  minor2 = SIMD.Float32x4.sub(minor2, SIMD.Float32x4.mul(row1, tmp1));

  tmp1   = SIMD.Float32x4.mul(row0, row2);
  tmp1   = SIMD.Float32x4.swizzle(tmp1, 1, 0, 3, 2);
  minor1 = SIMD.Float32x4.add(SIMD.Float32x4.mul(row3, tmp1), minor1);
  minor3 = SIMD.Float32x4.sub(minor3, SIMD.Float32x4.mul(row1, tmp1));
  tmp1   = SIMD.Float32x4.swizzle(tmp1, 2, 3, 0, 1);
  minor1 = SIMD.Float32x4.sub(minor1, SIMD.Float32x4.mul(row3, tmp1));
  minor3 = SIMD.Float32x4.add(SIMD.Float32x4.mul(row1, tmp1), minor3);

  // Compute matrix determinant
  det   = SIMD.Float32x4.mul(row0, minor0);
  det   = SIMD.Float32x4.add(SIMD.Float32x4.swizzle(det, 2, 3, 0, 1), det);
  det   = SIMD.Float32x4.add(SIMD.Float32x4.swizzle(det, 1, 0, 3, 2), det);
  tmp1  = SIMD.Float32x4.reciprocalApproximation(det);
  det   = SIMD.Float32x4.sub(
               SIMD.Float32x4.add(tmp1, tmp1),
               SIMD.Float32x4.mul(det, SIMD.Float32x4.mul(tmp1, tmp1)));
  det   = SIMD.Float32x4.swizzle(det, 0, 0, 0, 0);
  if (!det) {
      return null;
  }

  // Compute matrix inverse
  SIMD.Float32x4.store(out, 0,  SIMD.Float32x4.mul(det, minor0)); ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.SIMD.multiply"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.SIMD.</span>multiply (out, a, b)](#apidoc.element.gl-matrix.mat4.SIMD.multiply)
- description and source-code
```javascript
multiply = function (out, a, b) {
    var a0 = SIMD.Float32x4.load(a, 0);
    var a1 = SIMD.Float32x4.load(a, 4);
    var a2 = SIMD.Float32x4.load(a, 8);
    var a3 = SIMD.Float32x4.load(a, 12);

    var b0 = SIMD.Float32x4.load(b, 0);
    var out0 = SIMD.Float32x4.add(
                   SIMD.Float32x4.mul(SIMD.Float32x4.swizzle(b0, 0, 0, 0, 0), a0),
                   SIMD.Float32x4.add(
                       SIMD.Float32x4.mul(SIMD.Float32x4.swizzle(b0, 1, 1, 1, 1), a1),
                       SIMD.Float32x4.add(
                           SIMD.Float32x4.mul(SIMD.Float32x4.swizzle(b0, 2, 2, 2, 2), a2),
                           SIMD.Float32x4.mul(SIMD.Float32x4.swizzle(b0, 3, 3, 3, 3), a3))));
    SIMD.Float32x4.store(out, 0, out0);

    var b1 = SIMD.Float32x4.load(b, 4);
    var out1 = SIMD.Float32x4.add(
                   SIMD.Float32x4.mul(SIMD.Float32x4.swizzle(b1, 0, 0, 0, 0), a0),
                   SIMD.Float32x4.add(
                       SIMD.Float32x4.mul(SIMD.Float32x4.swizzle(b1, 1, 1, 1, 1), a1),
                       SIMD.Float32x4.add(
                           SIMD.Float32x4.mul(SIMD.Float32x4.swizzle(b1, 2, 2, 2, 2), a2),
                           SIMD.Float32x4.mul(SIMD.Float32x4.swizzle(b1, 3, 3, 3, 3), a3))));
    SIMD.Float32x4.store(out, 4, out1);

    var b2 = SIMD.Float32x4.load(b, 8);
    var out2 = SIMD.Float32x4.add(
                   SIMD.Float32x4.mul(SIMD.Float32x4.swizzle(b2, 0, 0, 0, 0), a0),
                   SIMD.Float32x4.add(
                       SIMD.Float32x4.mul(SIMD.Float32x4.swizzle(b2, 1, 1, 1, 1), a1),
                       SIMD.Float32x4.add(
                               SIMD.Float32x4.mul(SIMD.Float32x4.swizzle(b2, 2, 2, 2, 2), a2),
                               SIMD.Float32x4.mul(SIMD.Float32x4.swizzle(b2, 3, 3, 3, 3), a3))));
    SIMD.Float32x4.store(out, 8, out2);

    var b3 = SIMD.Float32x4.load(b, 12);
    var out3 = SIMD.Float32x4.add(
                   SIMD.Float32x4.mul(SIMD.Float32x4.swizzle(b3, 0, 0, 0, 0), a0),
                   SIMD.Float32x4.add(
                        SIMD.Float32x4.mul(SIMD.Float32x4.swizzle(b3, 1, 1, 1, 1), a1),
                        SIMD.Float32x4.add(
                            SIMD.Float32x4.mul(SIMD.Float32x4.swizzle(b3, 2, 2, 2, 2), a2),
                            SIMD.Float32x4.mul(SIMD.Float32x4.swizzle(b3, 3, 3, 3, 3), a3))));
    SIMD.Float32x4.store(out, 12, out3);

    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.SIMD.rotateX"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.SIMD.</span>rotateX (out, a, rad)](#apidoc.element.gl-matrix.mat4.SIMD.rotateX)
- description and source-code
```javascript
rotateX = function (out, a, rad) {
    var s = SIMD.Float32x4.splat(Math.sin(rad)),
        c = SIMD.Float32x4.splat(Math.cos(rad));

    if (a !== out) { // If the source and destination differ, copy the unchanged rows
      out[0]  = a[0];
      out[1]  = a[1];
      out[2]  = a[2];
      out[3]  = a[3];
      out[12] = a[12];
      out[13] = a[13];
      out[14] = a[14];
      out[15] = a[15];
    }

    // Perform axis-specific matrix multiplication
    var a_1 = SIMD.Float32x4.load(a, 4);
    var a_2 = SIMD.Float32x4.load(a, 8);
    SIMD.Float32x4.store(out, 4,
                         SIMD.Float32x4.add(SIMD.Float32x4.mul(a_1, c), SIMD.Float32x4.mul(a_2, s)));
    SIMD.Float32x4.store(out, 8,
                         SIMD.Float32x4.sub(SIMD.Float32x4.mul(a_2, c), SIMD.Float32x4.mul(a_1, s)));
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.SIMD.rotateY"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.SIMD.</span>rotateY (out, a, rad)](#apidoc.element.gl-matrix.mat4.SIMD.rotateY)
- description and source-code
```javascript
rotateY = function (out, a, rad) {
    var s = SIMD.Float32x4.splat(Math.sin(rad)),
        c = SIMD.Float32x4.splat(Math.cos(rad));

    if (a !== out) { // If the source and destination differ, copy the unchanged rows
        out[4]  = a[4];
        out[5]  = a[5];
        out[6]  = a[6];
        out[7]  = a[7];
        out[12] = a[12];
        out[13] = a[13];
        out[14] = a[14];
        out[15] = a[15];
    }

    // Perform axis-specific matrix multiplication
    var a_0 = SIMD.Float32x4.load(a, 0);
    var a_2 = SIMD.Float32x4.load(a, 8);
    SIMD.Float32x4.store(out, 0,
                         SIMD.Float32x4.sub(SIMD.Float32x4.mul(a_0, c), SIMD.Float32x4.mul(a_2, s)));
    SIMD.Float32x4.store(out, 8,
                         SIMD.Float32x4.add(SIMD.Float32x4.mul(a_0, s), SIMD.Float32x4.mul(a_2, c)));
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.SIMD.rotateZ"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.SIMD.</span>rotateZ (out, a, rad)](#apidoc.element.gl-matrix.mat4.SIMD.rotateZ)
- description and source-code
```javascript
rotateZ = function (out, a, rad) {
    var s = SIMD.Float32x4.splat(Math.sin(rad)),
        c = SIMD.Float32x4.splat(Math.cos(rad));

    if (a !== out) { // If the source and destination differ, copy the unchanged last row
        out[8]  = a[8];
        out[9]  = a[9];
        out[10] = a[10];
        out[11] = a[11];
        out[12] = a[12];
        out[13] = a[13];
        out[14] = a[14];
        out[15] = a[15];
    }

    // Perform axis-specific matrix multiplication
    var a_0 = SIMD.Float32x4.load(a, 0);
    var a_1 = SIMD.Float32x4.load(a, 4);
    SIMD.Float32x4.store(out, 0,
                         SIMD.Float32x4.add(SIMD.Float32x4.mul(a_0, c), SIMD.Float32x4.mul(a_1, s)));
    SIMD.Float32x4.store(out, 4,
                         SIMD.Float32x4.sub(SIMD.Float32x4.mul(a_1, c), SIMD.Float32x4.mul(a_0, s)));
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.SIMD.scale"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.SIMD.</span>scale (out, a, v)](#apidoc.element.gl-matrix.mat4.SIMD.scale)
- description and source-code
```javascript
scale = function (out, a, v) {
    var a0, a1, a2;
    var vec = SIMD.Float32x4(v[0], v[1], v[2], 0);

    a0 = SIMD.Float32x4.load(a, 0);
    SIMD.Float32x4.store(
        out, 0, SIMD.Float32x4.mul(a0, SIMD.Float32x4.swizzle(vec, 0, 0, 0, 0)));

    a1 = SIMD.Float32x4.load(a, 4);
    SIMD.Float32x4.store(
        out, 4, SIMD.Float32x4.mul(a1, SIMD.Float32x4.swizzle(vec, 1, 1, 1, 1)));

    a2 = SIMD.Float32x4.load(a, 8);
    SIMD.Float32x4.store(
        out, 8, SIMD.Float32x4.mul(a2, SIMD.Float32x4.swizzle(vec, 2, 2, 2, 2)));

    out[12] = a[12];
    out[13] = a[13];
    out[14] = a[14];
    out[15] = a[15];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.SIMD.translate"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.SIMD.</span>translate (out, a, v)](#apidoc.element.gl-matrix.mat4.SIMD.translate)
- description and source-code
```javascript
translate = function (out, a, v) {
    var a0 = SIMD.Float32x4.load(a, 0),
        a1 = SIMD.Float32x4.load(a, 4),
        a2 = SIMD.Float32x4.load(a, 8),
        a3 = SIMD.Float32x4.load(a, 12),
        vec = SIMD.Float32x4(v[0], v[1], v[2] , 0);

    if (a !== out) {
        out[0] = a[0]; out[1] = a[1]; out[2] = a[2]; out[3] = a[3];
        out[4] = a[4]; out[5] = a[5]; out[6] = a[6]; out[7] = a[7];
        out[8] = a[8]; out[9] = a[9]; out[10] = a[10]; out[11] = a[11];
    }

    a0 = SIMD.Float32x4.mul(a0, SIMD.Float32x4.swizzle(vec, 0, 0, 0, 0));
    a1 = SIMD.Float32x4.mul(a1, SIMD.Float32x4.swizzle(vec, 1, 1, 1, 1));
    a2 = SIMD.Float32x4.mul(a2, SIMD.Float32x4.swizzle(vec, 2, 2, 2, 2));

    var t0 = SIMD.Float32x4.add(a0, SIMD.Float32x4.add(a1, SIMD.Float32x4.add(a2, a3)));
    SIMD.Float32x4.store(out, 12, t0);

    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.SIMD.transpose"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.SIMD.</span>transpose (out, a)](#apidoc.element.gl-matrix.mat4.SIMD.transpose)
- description and source-code
```javascript
transpose = function (out, a) {
    var a0, a1, a2, a3,
        tmp01, tmp23,
        out0, out1, out2, out3;

    a0 = SIMD.Float32x4.load(a, 0);
    a1 = SIMD.Float32x4.load(a, 4);
    a2 = SIMD.Float32x4.load(a, 8);
    a3 = SIMD.Float32x4.load(a, 12);

    tmp01 = SIMD.Float32x4.shuffle(a0, a1, 0, 1, 4, 5);
    tmp23 = SIMD.Float32x4.shuffle(a2, a3, 0, 1, 4, 5);
    out0  = SIMD.Float32x4.shuffle(tmp01, tmp23, 0, 2, 4, 6);
    out1  = SIMD.Float32x4.shuffle(tmp01, tmp23, 1, 3, 5, 7);
    SIMD.Float32x4.store(out, 0,  out0);
    SIMD.Float32x4.store(out, 4,  out1);

    tmp01 = SIMD.Float32x4.shuffle(a0, a1, 2, 3, 6, 7);
    tmp23 = SIMD.Float32x4.shuffle(a2, a3, 2, 3, 6, 7);
    out2  = SIMD.Float32x4.shuffle(tmp01, tmp23, 0, 2, 4, 6);
    out3  = SIMD.Float32x4.shuffle(tmp01, tmp23, 1, 3, 5, 7);
    SIMD.Float32x4.store(out, 8,  out2);
    SIMD.Float32x4.store(out, 12, out3);

    return out;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gl-matrix.mat4.scalar"></a>[module gl-matrix.mat4.scalar](#apidoc.module.gl-matrix.mat4.scalar)

#### <a name="apidoc.element.gl-matrix.mat4.scalar.adjoint"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.scalar.</span>adjoint (out, a)](#apidoc.element.gl-matrix.mat4.scalar.adjoint)
- description and source-code
```javascript
adjoint = function (out, a) {
    var a00 = a[0], a01 = a[1], a02 = a[2], a03 = a[3],
        a10 = a[4], a11 = a[5], a12 = a[6], a13 = a[7],
        a20 = a[8], a21 = a[9], a22 = a[10], a23 = a[11],
        a30 = a[12], a31 = a[13], a32 = a[14], a33 = a[15];

    out[0]  =  (a11 * (a22 * a33 - a23 * a32) - a21 * (a12 * a33 - a13 * a32) + a31 * (a12 * a23 - a13 * a22));
    out[1]  = -(a01 * (a22 * a33 - a23 * a32) - a21 * (a02 * a33 - a03 * a32) + a31 * (a02 * a23 - a03 * a22));
    out[2]  =  (a01 * (a12 * a33 - a13 * a32) - a11 * (a02 * a33 - a03 * a32) + a31 * (a02 * a13 - a03 * a12));
    out[3]  = -(a01 * (a12 * a23 - a13 * a22) - a11 * (a02 * a23 - a03 * a22) + a21 * (a02 * a13 - a03 * a12));
    out[4]  = -(a10 * (a22 * a33 - a23 * a32) - a20 * (a12 * a33 - a13 * a32) + a30 * (a12 * a23 - a13 * a22));
    out[5]  =  (a00 * (a22 * a33 - a23 * a32) - a20 * (a02 * a33 - a03 * a32) + a30 * (a02 * a23 - a03 * a22));
    out[6]  = -(a00 * (a12 * a33 - a13 * a32) - a10 * (a02 * a33 - a03 * a32) + a30 * (a02 * a13 - a03 * a12));
    out[7]  =  (a00 * (a12 * a23 - a13 * a22) - a10 * (a02 * a23 - a03 * a22) + a20 * (a02 * a13 - a03 * a12));
    out[8]  =  (a10 * (a21 * a33 - a23 * a31) - a20 * (a11 * a33 - a13 * a31) + a30 * (a11 * a23 - a13 * a21));
    out[9]  = -(a00 * (a21 * a33 - a23 * a31) - a20 * (a01 * a33 - a03 * a31) + a30 * (a01 * a23 - a03 * a21));
    out[10] =  (a00 * (a11 * a33 - a13 * a31) - a10 * (a01 * a33 - a03 * a31) + a30 * (a01 * a13 - a03 * a11));
    out[11] = -(a00 * (a11 * a23 - a13 * a21) - a10 * (a01 * a23 - a03 * a21) + a20 * (a01 * a13 - a03 * a11));
    out[12] = -(a10 * (a21 * a32 - a22 * a31) - a20 * (a11 * a32 - a12 * a31) + a30 * (a11 * a22 - a12 * a21));
    out[13] =  (a00 * (a21 * a32 - a22 * a31) - a20 * (a01 * a32 - a02 * a31) + a30 * (a01 * a22 - a02 * a21));
    out[14] = -(a00 * (a11 * a32 - a12 * a31) - a10 * (a01 * a32 - a02 * a31) + a30 * (a01 * a12 - a02 * a11));
    out[15] =  (a00 * (a11 * a22 - a12 * a21) - a10 * (a01 * a22 - a02 * a21) + a20 * (a01 * a12 - a02 * a11));
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.scalar.invert"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.scalar.</span>invert (out, a)](#apidoc.element.gl-matrix.mat4.scalar.invert)
- description and source-code
```javascript
invert = function (out, a) {
    var a00 = a[0], a01 = a[1], a02 = a[2], a03 = a[3],
        a10 = a[4], a11 = a[5], a12 = a[6], a13 = a[7],
        a20 = a[8], a21 = a[9], a22 = a[10], a23 = a[11],
        a30 = a[12], a31 = a[13], a32 = a[14], a33 = a[15],

        b00 = a00 * a11 - a01 * a10,
        b01 = a00 * a12 - a02 * a10,
        b02 = a00 * a13 - a03 * a10,
        b03 = a01 * a12 - a02 * a11,
        b04 = a01 * a13 - a03 * a11,
        b05 = a02 * a13 - a03 * a12,
        b06 = a20 * a31 - a21 * a30,
        b07 = a20 * a32 - a22 * a30,
        b08 = a20 * a33 - a23 * a30,
        b09 = a21 * a32 - a22 * a31,
        b10 = a21 * a33 - a23 * a31,
        b11 = a22 * a33 - a23 * a32,

        // Calculate the determinant
        det = b00 * b11 - b01 * b10 + b02 * b09 + b03 * b08 - b04 * b07 + b05 * b06;

    if (!det) {
        return null;
    }
    det = 1.0 / det;

    out[0] = (a11 * b11 - a12 * b10 + a13 * b09) * det;
    out[1] = (a02 * b10 - a01 * b11 - a03 * b09) * det;
    out[2] = (a31 * b05 - a32 * b04 + a33 * b03) * det;
    out[3] = (a22 * b04 - a21 * b05 - a23 * b03) * det;
    out[4] = (a12 * b08 - a10 * b11 - a13 * b07) * det;
    out[5] = (a00 * b11 - a02 * b08 + a03 * b07) * det;
    out[6] = (a32 * b02 - a30 * b05 - a33 * b01) * det;
    out[7] = (a20 * b05 - a22 * b02 + a23 * b01) * det;
    out[8] = (a10 * b10 - a11 * b08 + a13 * b06) * det;
    out[9] = (a01 * b08 - a00 * b10 - a03 * b06) * det;
    out[10] = (a30 * b04 - a31 * b02 + a33 * b00) * det;
    out[11] = (a21 * b02 - a20 * b04 - a23 * b00) * det;
    out[12] = (a11 * b07 - a10 * b09 - a12 * b06) * det;
    out[13] = (a00 * b09 - a01 * b07 + a02 * b06) * det;
    out[14] = (a31 * b01 - a30 * b03 - a32 * b00) * det;
    out[15] = (a20 * b03 - a21 * b01 + a22 * b00) * det;

    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.scalar.multiply"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.scalar.</span>multiply (out, a, b)](#apidoc.element.gl-matrix.mat4.scalar.multiply)
- description and source-code
```javascript
multiply = function (out, a, b) {
    var a00 = a[0], a01 = a[1], a02 = a[2], a03 = a[3],
        a10 = a[4], a11 = a[5], a12 = a[6], a13 = a[7],
        a20 = a[8], a21 = a[9], a22 = a[10], a23 = a[11],
        a30 = a[12], a31 = a[13], a32 = a[14], a33 = a[15];

    // Cache only the current line of the second matrix
    var b0  = b[0], b1 = b[1], b2 = b[2], b3 = b[3];
    out[0] = b0*a00 + b1*a10 + b2*a20 + b3*a30;
    out[1] = b0*a01 + b1*a11 + b2*a21 + b3*a31;
    out[2] = b0*a02 + b1*a12 + b2*a22 + b3*a32;
    out[3] = b0*a03 + b1*a13 + b2*a23 + b3*a33;

    b0 = b[4]; b1 = b[5]; b2 = b[6]; b3 = b[7];
    out[4] = b0*a00 + b1*a10 + b2*a20 + b3*a30;
    out[5] = b0*a01 + b1*a11 + b2*a21 + b3*a31;
    out[6] = b0*a02 + b1*a12 + b2*a22 + b3*a32;
    out[7] = b0*a03 + b1*a13 + b2*a23 + b3*a33;

    b0 = b[8]; b1 = b[9]; b2 = b[10]; b3 = b[11];
    out[8] = b0*a00 + b1*a10 + b2*a20 + b3*a30;
    out[9] = b0*a01 + b1*a11 + b2*a21 + b3*a31;
    out[10] = b0*a02 + b1*a12 + b2*a22 + b3*a32;
    out[11] = b0*a03 + b1*a13 + b2*a23 + b3*a33;

    b0 = b[12]; b1 = b[13]; b2 = b[14]; b3 = b[15];
    out[12] = b0*a00 + b1*a10 + b2*a20 + b3*a30;
    out[13] = b0*a01 + b1*a11 + b2*a21 + b3*a31;
    out[14] = b0*a02 + b1*a12 + b2*a22 + b3*a32;
    out[15] = b0*a03 + b1*a13 + b2*a23 + b3*a33;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.scalar.rotateX"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.scalar.</span>rotateX (out, a, rad)](#apidoc.element.gl-matrix.mat4.scalar.rotateX)
- description and source-code
```javascript
rotateX = function (out, a, rad) {
    var s = Math.sin(rad),
        c = Math.cos(rad),
        a10 = a[4],
        a11 = a[5],
        a12 = a[6],
        a13 = a[7],
        a20 = a[8],
        a21 = a[9],
        a22 = a[10],
        a23 = a[11];

    if (a !== out) { // If the source and destination differ, copy the unchanged rows
        out[0]  = a[0];
        out[1]  = a[1];
        out[2]  = a[2];
        out[3]  = a[3];
        out[12] = a[12];
        out[13] = a[13];
        out[14] = a[14];
        out[15] = a[15];
    }

    // Perform axis-specific matrix multiplication
    out[4] = a10 * c + a20 * s;
    out[5] = a11 * c + a21 * s;
    out[6] = a12 * c + a22 * s;
    out[7] = a13 * c + a23 * s;
    out[8] = a20 * c - a10 * s;
    out[9] = a21 * c - a11 * s;
    out[10] = a22 * c - a12 * s;
    out[11] = a23 * c - a13 * s;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.scalar.rotateY"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.scalar.</span>rotateY (out, a, rad)](#apidoc.element.gl-matrix.mat4.scalar.rotateY)
- description and source-code
```javascript
rotateY = function (out, a, rad) {
    var s = Math.sin(rad),
        c = Math.cos(rad),
        a00 = a[0],
        a01 = a[1],
        a02 = a[2],
        a03 = a[3],
        a20 = a[8],
        a21 = a[9],
        a22 = a[10],
        a23 = a[11];

    if (a !== out) { // If the source and destination differ, copy the unchanged rows
        out[4]  = a[4];
        out[5]  = a[5];
        out[6]  = a[6];
        out[7]  = a[7];
        out[12] = a[12];
        out[13] = a[13];
        out[14] = a[14];
        out[15] = a[15];
    }

    // Perform axis-specific matrix multiplication
    out[0] = a00 * c - a20 * s;
    out[1] = a01 * c - a21 * s;
    out[2] = a02 * c - a22 * s;
    out[3] = a03 * c - a23 * s;
    out[8] = a00 * s + a20 * c;
    out[9] = a01 * s + a21 * c;
    out[10] = a02 * s + a22 * c;
    out[11] = a03 * s + a23 * c;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.scalar.rotateZ"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.scalar.</span>rotateZ (out, a, rad)](#apidoc.element.gl-matrix.mat4.scalar.rotateZ)
- description and source-code
```javascript
rotateZ = function (out, a, rad) {
    var s = Math.sin(rad),
        c = Math.cos(rad),
        a00 = a[0],
        a01 = a[1],
        a02 = a[2],
        a03 = a[3],
        a10 = a[4],
        a11 = a[5],
        a12 = a[6],
        a13 = a[7];

    if (a !== out) { // If the source and destination differ, copy the unchanged last row
        out[8]  = a[8];
        out[9]  = a[9];
        out[10] = a[10];
        out[11] = a[11];
        out[12] = a[12];
        out[13] = a[13];
        out[14] = a[14];
        out[15] = a[15];
    }

    // Perform axis-specific matrix multiplication
    out[0] = a00 * c + a10 * s;
    out[1] = a01 * c + a11 * s;
    out[2] = a02 * c + a12 * s;
    out[3] = a03 * c + a13 * s;
    out[4] = a10 * c - a00 * s;
    out[5] = a11 * c - a01 * s;
    out[6] = a12 * c - a02 * s;
    out[7] = a13 * c - a03 * s;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.scalar.scale"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.scalar.</span>scale (out, a, v)](#apidoc.element.gl-matrix.mat4.scalar.scale)
- description and source-code
```javascript
scale = function (out, a, v) {
    var x = v[0], y = v[1], z = v[2];

    out[0] = a[0] * x;
    out[1] = a[1] * x;
    out[2] = a[2] * x;
    out[3] = a[3] * x;
    out[4] = a[4] * y;
    out[5] = a[5] * y;
    out[6] = a[6] * y;
    out[7] = a[7] * y;
    out[8] = a[8] * z;
    out[9] = a[9] * z;
    out[10] = a[10] * z;
    out[11] = a[11] * z;
    out[12] = a[12];
    out[13] = a[13];
    out[14] = a[14];
    out[15] = a[15];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.scalar.translate"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.scalar.</span>translate (out, a, v)](#apidoc.element.gl-matrix.mat4.scalar.translate)
- description and source-code
```javascript
translate = function (out, a, v) {
    var x = v[0], y = v[1], z = v[2],
        a00, a01, a02, a03,
        a10, a11, a12, a13,
        a20, a21, a22, a23;

    if (a === out) {
        out[12] = a[0] * x + a[4] * y + a[8] * z + a[12];
        out[13] = a[1] * x + a[5] * y + a[9] * z + a[13];
        out[14] = a[2] * x + a[6] * y + a[10] * z + a[14];
        out[15] = a[3] * x + a[7] * y + a[11] * z + a[15];
    } else {
        a00 = a[0]; a01 = a[1]; a02 = a[2]; a03 = a[3];
        a10 = a[4]; a11 = a[5]; a12 = a[6]; a13 = a[7];
        a20 = a[8]; a21 = a[9]; a22 = a[10]; a23 = a[11];

        out[0] = a00; out[1] = a01; out[2] = a02; out[3] = a03;
        out[4] = a10; out[5] = a11; out[6] = a12; out[7] = a13;
        out[8] = a20; out[9] = a21; out[10] = a22; out[11] = a23;

        out[12] = a00 * x + a10 * y + a20 * z + a[12];
        out[13] = a01 * x + a11 * y + a21 * z + a[13];
        out[14] = a02 * x + a12 * y + a22 * z + a[14];
        out[15] = a03 * x + a13 * y + a23 * z + a[15];
    }

    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.mat4.scalar.transpose"></a>[function <span class="apidocSignatureSpan">gl-matrix.mat4.scalar.</span>transpose (out, a)](#apidoc.element.gl-matrix.mat4.scalar.transpose)
- description and source-code
```javascript
transpose = function (out, a) {
    // If we are transposing ourselves we can skip a few steps but have to cache some values
    if (out === a) {
        var a01 = a[1], a02 = a[2], a03 = a[3],
            a12 = a[6], a13 = a[7],
            a23 = a[11];

        out[1] = a[4];
        out[2] = a[8];
        out[3] = a[12];
        out[4] = a01;
        out[6] = a[9];
        out[7] = a[13];
        out[8] = a02;
        out[9] = a12;
        out[11] = a[14];
        out[12] = a03;
        out[13] = a13;
        out[14] = a23;
    } else {
        out[0] = a[0];
        out[1] = a[4];
        out[2] = a[8];
        out[3] = a[12];
        out[4] = a[1];
        out[5] = a[5];
        out[6] = a[9];
        out[7] = a[13];
        out[8] = a[2];
        out[9] = a[6];
        out[10] = a[10];
        out[11] = a[14];
        out[12] = a[3];
        out[13] = a[7];
        out[14] = a[11];
        out[15] = a[15];
    }

    return out;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gl-matrix.quat"></a>[module gl-matrix.quat](#apidoc.module.gl-matrix.quat)

#### <a name="apidoc.element.gl-matrix.quat.add"></a>[function <span class="apidocSignatureSpan">gl-matrix.quat.</span>add (out, a, b)](#apidoc.element.gl-matrix.quat.add)
- description and source-code
```javascript
add = function (out, a, b) {
    out[0] = a[0] + b[0];
    out[1] = a[1] + b[1];
    out[2] = a[2] + b[2];
    out[3] = a[3] + b[3];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.quat.calculateW"></a>[function <span class="apidocSignatureSpan">gl-matrix.quat.</span>calculateW (out, a)](#apidoc.element.gl-matrix.quat.calculateW)
- description and source-code
```javascript
calculateW = function (out, a) {
    var x = a[0], y = a[1], z = a[2];

    out[0] = x;
    out[1] = y;
    out[2] = z;
    out[3] = Math.sqrt(Math.abs(1.0 - x * x - y * y - z * z));
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.quat.clone"></a>[function <span class="apidocSignatureSpan">gl-matrix.quat.</span>clone (a)](#apidoc.element.gl-matrix.quat.clone)
- description and source-code
```javascript
clone = function (a) {
    var out = new glMatrix.ARRAY_TYPE(4);
    out[0] = a[0];
    out[1] = a[1];
    out[2] = a[2];
    out[3] = a[3];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.quat.conjugate"></a>[function <span class="apidocSignatureSpan">gl-matrix.quat.</span>conjugate (out, a)](#apidoc.element.gl-matrix.quat.conjugate)
- description and source-code
```javascript
conjugate = function (out, a) {
    out[0] = -a[0];
    out[1] = -a[1];
    out[2] = -a[2];
    out[3] = a[3];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.quat.copy"></a>[function <span class="apidocSignatureSpan">gl-matrix.quat.</span>copy (out, a)](#apidoc.element.gl-matrix.quat.copy)
- description and source-code
```javascript
copy = function (out, a) {
    out[0] = a[0];
    out[1] = a[1];
    out[2] = a[2];
    out[3] = a[3];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.quat.create"></a>[function <span class="apidocSignatureSpan">gl-matrix.quat.</span>create ()](#apidoc.element.gl-matrix.quat.create)
- description and source-code
```javascript
create = function () {
    var out = new glMatrix.ARRAY_TYPE(4);
    out[0] = 0;
    out[1] = 0;
    out[2] = 0;
    out[3] = 1;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.quat.dot"></a>[function <span class="apidocSignatureSpan">gl-matrix.quat.</span>dot (a, b)](#apidoc.element.gl-matrix.quat.dot)
- description and source-code
```javascript
dot = function (a, b) {
    return a[0] * b[0] + a[1] * b[1] + a[2] * b[2] + a[3] * b[3];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.quat.equals"></a>[function <span class="apidocSignatureSpan">gl-matrix.quat.</span>equals (a, b)](#apidoc.element.gl-matrix.quat.equals)
- description and source-code
```javascript
equals = function (a, b) {
    var a0 = a[0], a1 = a[1], a2 = a[2], a3 = a[3];
    var b0 = b[0], b1 = b[1], b2 = b[2], b3 = b[3];
    return (Math.abs(a0 - b0) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a0), Math.abs(b0)) &&
            Math.abs(a1 - b1) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a1), Math.abs(b1)) &&
            Math.abs(a2 - b2) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a2), Math.abs(b2)) &&
            Math.abs(a3 - b3) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a3), Math.abs(b3)));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.quat.exactEquals"></a>[function <span class="apidocSignatureSpan">gl-matrix.quat.</span>exactEquals (a, b)](#apidoc.element.gl-matrix.quat.exactEquals)
- description and source-code
```javascript
exactEquals = function (a, b) {
    return a[0] === b[0] && a[1] === b[1] && a[2] === b[2] && a[3] === b[3];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.quat.fromMat3"></a>[function <span class="apidocSignatureSpan">gl-matrix.quat.</span>fromMat3 (out, m)](#apidoc.element.gl-matrix.quat.fromMat3)
- description and source-code
```javascript
fromMat3 = function (out, m) {
    // Algorithm in Ken Shoemake's article in 1987 SIGGRAPH course notes
    // article "Quaternion Calculus and Fast Animation".
    var fTrace = m[0] + m[4] + m[8];
    var fRoot;

    if ( fTrace > 0.0 ) {
        // |w| > 1/2, may as well choose w > 1/2
        fRoot = Math.sqrt(fTrace + 1.0);  // 2w
        out[3] = 0.5 * fRoot;
        fRoot = 0.5/fRoot;  // 1/(4w)
        out[0] = (m[5]-m[7])*fRoot;
        out[1] = (m[6]-m[2])*fRoot;
        out[2] = (m[1]-m[3])*fRoot;
    } else {
        // |w| <= 1/2
        var i = 0;
        if ( m[4] > m[0] )
          i = 1;
        if ( m[8] > m[i*3+i] )
          i = 2;
        var j = (i+1)%3;
        var k = (i+2)%3;

        fRoot = Math.sqrt(m[i*3+i]-m[j*3+j]-m[k*3+k] + 1.0);
        out[i] = 0.5 * fRoot;
        fRoot = 0.5 / fRoot;
        out[3] = (m[j*3+k] - m[k*3+j]) * fRoot;
        out[j] = (m[j*3+i] + m[i*3+j]) * fRoot;
        out[k] = (m[k*3+i] + m[i*3+k]) * fRoot;
    }

    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.quat.fromValues"></a>[function <span class="apidocSignatureSpan">gl-matrix.quat.</span>fromValues (x, y, z, w)](#apidoc.element.gl-matrix.quat.fromValues)
- description and source-code
```javascript
fromValues = function (x, y, z, w) {
    var out = new glMatrix.ARRAY_TYPE(4);
    out[0] = x;
    out[1] = y;
    out[2] = z;
    out[3] = w;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.quat.getAxisAngle"></a>[function <span class="apidocSignatureSpan">gl-matrix.quat.</span>getAxisAngle (out_axis, q)](#apidoc.element.gl-matrix.quat.getAxisAngle)
- description and source-code
```javascript
getAxisAngle = function (out_axis, q) {
    var rad = Math.acos(q[3]) * 2.0;
    var s = Math.sin(rad / 2.0);
    if (s != 0.0) {
        out_axis[0] = q[0] / s;
        out_axis[1] = q[1] / s;
        out_axis[2] = q[2] / s;
    } else {
        // If s is zero, return any axis (no rotation - axis does not matter)
        out_axis[0] = 1;
        out_axis[1] = 0;
        out_axis[2] = 0;
    }
    return rad;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.quat.identity"></a>[function <span class="apidocSignatureSpan">gl-matrix.quat.</span>identity (out)](#apidoc.element.gl-matrix.quat.identity)
- description and source-code
```javascript
identity = function (out) {
    out[0] = 0;
    out[1] = 0;
    out[2] = 0;
    out[3] = 1;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.quat.invert"></a>[function <span class="apidocSignatureSpan">gl-matrix.quat.</span>invert (out, a)](#apidoc.element.gl-matrix.quat.invert)
- description and source-code
```javascript
invert = function (out, a) {
    var a0 = a[0], a1 = a[1], a2 = a[2], a3 = a[3],
        dot = a0*a0 + a1*a1 + a2*a2 + a3*a3,
        invDot = dot ? 1.0/dot : 0;

    // TODO: Would be faster to return [0,0,0,0] immediately if dot == 0

    out[0] = -a0*invDot;
    out[1] = -a1*invDot;
    out[2] = -a2*invDot;
    out[3] = a3*invDot;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.quat.len"></a>[function <span class="apidocSignatureSpan">gl-matrix.quat.</span>len (a)](#apidoc.element.gl-matrix.quat.len)
- description and source-code
```javascript
len = function (a) {
    var x = a[0],
        y = a[1],
        z = a[2],
        w = a[3];
    return Math.sqrt(x*x + y*y + z*z + w*w);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.quat.length"></a>[function <span class="apidocSignatureSpan">gl-matrix.quat.</span>length (a)](#apidoc.element.gl-matrix.quat.length)
- description and source-code
```javascript
length = function (a) {
    var x = a[0],
        y = a[1],
        z = a[2],
        w = a[3];
    return Math.sqrt(x*x + y*y + z*z + w*w);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.quat.lerp"></a>[function <span class="apidocSignatureSpan">gl-matrix.quat.</span>lerp (out, a, b, t)](#apidoc.element.gl-matrix.quat.lerp)
- description and source-code
```javascript
lerp = function (out, a, b, t) {
    var ax = a[0],
        ay = a[1],
        az = a[2],
        aw = a[3];
    out[0] = ax + t * (b[0] - ax);
    out[1] = ay + t * (b[1] - ay);
    out[2] = az + t * (b[2] - az);
    out[3] = aw + t * (b[3] - aw);
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.quat.mul"></a>[function <span class="apidocSignatureSpan">gl-matrix.quat.</span>mul (out, a, b)](#apidoc.element.gl-matrix.quat.mul)
- description and source-code
```javascript
mul = function (out, a, b) {
    var ax = a[0], ay = a[1], az = a[2], aw = a[3],
        bx = b[0], by = b[1], bz = b[2], bw = b[3];

    out[0] = ax * bw + aw * bx + ay * bz - az * by;
    out[1] = ay * bw + aw * by + az * bx - ax * bz;
    out[2] = az * bw + aw * bz + ax * by - ay * bx;
    out[3] = aw * bw - ax * bx - ay * by - az * bz;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.quat.multiply"></a>[function <span class="apidocSignatureSpan">gl-matrix.quat.</span>multiply (out, a, b)](#apidoc.element.gl-matrix.quat.multiply)
- description and source-code
```javascript
multiply = function (out, a, b) {
    var ax = a[0], ay = a[1], az = a[2], aw = a[3],
        bx = b[0], by = b[1], bz = b[2], bw = b[3];

    out[0] = ax * bw + aw * bx + ay * bz - az * by;
    out[1] = ay * bw + aw * by + az * bx - ax * bz;
    out[2] = az * bw + aw * bz + ax * by - ay * bx;
    out[3] = aw * bw - ax * bx - ay * by - az * bz;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.quat.normalize"></a>[function <span class="apidocSignatureSpan">gl-matrix.quat.</span>normalize (out, a)](#apidoc.element.gl-matrix.quat.normalize)
- description and source-code
```javascript
normalize = function (out, a) {
    var x = a[0],
        y = a[1],
        z = a[2],
        w = a[3];
    var len = x*x + y*y + z*z + w*w;
    if (len > 0) {
        len = 1 / Math.sqrt(len);
        out[0] = x * len;
        out[1] = y * len;
        out[2] = z * len;
        out[3] = w * len;
    }
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.quat.rotateX"></a>[function <span class="apidocSignatureSpan">gl-matrix.quat.</span>rotateX (out, a, rad)](#apidoc.element.gl-matrix.quat.rotateX)
- description and source-code
```javascript
rotateX = function (out, a, rad) {
    rad *= 0.5;

    var ax = a[0], ay = a[1], az = a[2], aw = a[3],
        bx = Math.sin(rad), bw = Math.cos(rad);

    out[0] = ax * bw + aw * bx;
    out[1] = ay * bw + az * bx;
    out[2] = az * bw - ay * bx;
    out[3] = aw * bw - ax * bx;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.quat.rotateY"></a>[function <span class="apidocSignatureSpan">gl-matrix.quat.</span>rotateY (out, a, rad)](#apidoc.element.gl-matrix.quat.rotateY)
- description and source-code
```javascript
rotateY = function (out, a, rad) {
    rad *= 0.5;

    var ax = a[0], ay = a[1], az = a[2], aw = a[3],
        by = Math.sin(rad), bw = Math.cos(rad);

    out[0] = ax * bw - az * by;
    out[1] = ay * bw + aw * by;
    out[2] = az * bw + ax * by;
    out[3] = aw * bw - ay * by;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.quat.rotateZ"></a>[function <span class="apidocSignatureSpan">gl-matrix.quat.</span>rotateZ (out, a, rad)](#apidoc.element.gl-matrix.quat.rotateZ)
- description and source-code
```javascript
rotateZ = function (out, a, rad) {
    rad *= 0.5;

    var ax = a[0], ay = a[1], az = a[2], aw = a[3],
        bz = Math.sin(rad), bw = Math.cos(rad);

    out[0] = ax * bw + ay * bz;
    out[1] = ay * bw - ax * bz;
    out[2] = az * bw + aw * bz;
    out[3] = aw * bw - az * bz;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.quat.rotationTo"></a>[function <span class="apidocSignatureSpan">gl-matrix.quat.</span>rotationTo (out, a, b)](#apidoc.element.gl-matrix.quat.rotationTo)
- description and source-code
```javascript
rotationTo = function (out, a, b) {
    var dot = vec3.dot(a, b);
    if (dot < -0.999999) {
        vec3.cross(tmpvec3, xUnitVec3, a);
        if (vec3.length(tmpvec3) < 0.000001)
            vec3.cross(tmpvec3, yUnitVec3, a);
        vec3.normalize(tmpvec3, tmpvec3);
        quat.setAxisAngle(out, tmpvec3, Math.PI);
        return out;
    } else if (dot > 0.999999) {
        out[0] = 0;
        out[1] = 0;
        out[2] = 0;
        out[3] = 1;
        return out;
    } else {
        vec3.cross(tmpvec3, a, b);
        out[0] = tmpvec3[0];
        out[1] = tmpvec3[1];
        out[2] = tmpvec3[2];
        out[3] = 1 + dot;
        return quat.normalize(out, out);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.quat.scale"></a>[function <span class="apidocSignatureSpan">gl-matrix.quat.</span>scale (out, a, b)](#apidoc.element.gl-matrix.quat.scale)
- description and source-code
```javascript
scale = function (out, a, b) {
    out[0] = a[0] * b;
    out[1] = a[1] * b;
    out[2] = a[2] * b;
    out[3] = a[3] * b;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.quat.set"></a>[function <span class="apidocSignatureSpan">gl-matrix.quat.</span>set (out, x, y, z, w)](#apidoc.element.gl-matrix.quat.set)
- description and source-code
```javascript
set = function (out, x, y, z, w) {
    out[0] = x;
    out[1] = y;
    out[2] = z;
    out[3] = w;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.quat.setAxes"></a>[function <span class="apidocSignatureSpan">gl-matrix.quat.</span>setAxes (out, view, right, up)](#apidoc.element.gl-matrix.quat.setAxes)
- description and source-code
```javascript
setAxes = function (out, view, right, up) {
    matr[0] = right[0];
    matr[3] = right[1];
    matr[6] = right[2];

    matr[1] = up[0];
    matr[4] = up[1];
    matr[7] = up[2];

    matr[2] = -view[0];
    matr[5] = -view[1];
    matr[8] = -view[2];

    return quat.normalize(out, quat.fromMat3(out, matr));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.quat.setAxisAngle"></a>[function <span class="apidocSignatureSpan">gl-matrix.quat.</span>setAxisAngle (out, axis, rad)](#apidoc.element.gl-matrix.quat.setAxisAngle)
- description and source-code
```javascript
setAxisAngle = function (out, axis, rad) {
    rad = rad * 0.5;
    var s = Math.sin(rad);
    out[0] = s * axis[0];
    out[1] = s * axis[1];
    out[2] = s * axis[2];
    out[3] = Math.cos(rad);
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.quat.slerp"></a>[function <span class="apidocSignatureSpan">gl-matrix.quat.</span>slerp (out, a, b, t)](#apidoc.element.gl-matrix.quat.slerp)
- description and source-code
```javascript
slerp = function (out, a, b, t) {
    // benchmarks:
    //    http://jsperf.com/quaternion-slerp-implementations

    var ax = a[0], ay = a[1], az = a[2], aw = a[3],
        bx = b[0], by = b[1], bz = b[2], bw = b[3];

    var        omega, cosom, sinom, scale0, scale1;

    // calc cosine
    cosom = ax * bx + ay * by + az * bz + aw * bw;
    // adjust signs (if necessary)
    if ( cosom < 0.0 ) {
        cosom = -cosom;
        bx = - bx;
        by = - by;
        bz = - bz;
        bw = - bw;
    }
    // calculate coefficients
    if ( (1.0 - cosom) > 0.000001 ) {
        // standard case (slerp)
        omega  = Math.acos(cosom);
        sinom  = Math.sin(omega);
        scale0 = Math.sin((1.0 - t) * omega) / sinom;
        scale1 = Math.sin(t * omega) / sinom;
    } else {
        // "from" and "to" quaternions are very close
        //  ... so we can do a linear interpolation
        scale0 = 1.0 - t;
        scale1 = t;
    }
    // calculate final values
    out[0] = scale0 * ax + scale1 * bx;
    out[1] = scale0 * ay + scale1 * by;
    out[2] = scale0 * az + scale1 * bz;
    out[3] = scale0 * aw + scale1 * bw;

    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.quat.sqlerp"></a>[function <span class="apidocSignatureSpan">gl-matrix.quat.</span>sqlerp (out, a, b, c, d, t)](#apidoc.element.gl-matrix.quat.sqlerp)
- description and source-code
```javascript
sqlerp = function (out, a, b, c, d, t) {
  quat.slerp(temp1, a, d, t);
  quat.slerp(temp2, b, c, t);
  quat.slerp(out, temp1, temp2, 2 * t * (1 - t));

  return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.quat.sqrLen"></a>[function <span class="apidocSignatureSpan">gl-matrix.quat.</span>sqrLen (a)](#apidoc.element.gl-matrix.quat.sqrLen)
- description and source-code
```javascript
sqrLen = function (a) {
    var x = a[0],
        y = a[1],
        z = a[2],
        w = a[3];
    return x*x + y*y + z*z + w*w;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.quat.squaredLength"></a>[function <span class="apidocSignatureSpan">gl-matrix.quat.</span>squaredLength (a)](#apidoc.element.gl-matrix.quat.squaredLength)
- description and source-code
```javascript
squaredLength = function (a) {
    var x = a[0],
        y = a[1],
        z = a[2],
        w = a[3];
    return x*x + y*y + z*z + w*w;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.quat.str"></a>[function <span class="apidocSignatureSpan">gl-matrix.quat.</span>str (a)](#apidoc.element.gl-matrix.quat.str)
- description and source-code
```javascript
str = function (a) {
    return 'quat(' + a[0] + ', ' + a[1] + ', ' + a[2] + ', ' + a[3] + ')';
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gl-matrix.vec2"></a>[module gl-matrix.vec2](#apidoc.module.gl-matrix.vec2)

#### <a name="apidoc.element.gl-matrix.vec2.add"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>add (out, a, b)](#apidoc.element.gl-matrix.vec2.add)
- description and source-code
```javascript
add = function (out, a, b) {
    out[0] = a[0] + b[0];
    out[1] = a[1] + b[1];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.ceil"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>ceil (out, a)](#apidoc.element.gl-matrix.vec2.ceil)
- description and source-code
```javascript
ceil = function (out, a) {
    out[0] = Math.ceil(a[0]);
    out[1] = Math.ceil(a[1]);
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.clone"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>clone (a)](#apidoc.element.gl-matrix.vec2.clone)
- description and source-code
```javascript
clone = function (a) {
    var out = new glMatrix.ARRAY_TYPE(2);
    out[0] = a[0];
    out[1] = a[1];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.copy"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>copy (out, a)](#apidoc.element.gl-matrix.vec2.copy)
- description and source-code
```javascript
copy = function (out, a) {
    out[0] = a[0];
    out[1] = a[1];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.create"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>create ()](#apidoc.element.gl-matrix.vec2.create)
- description and source-code
```javascript
create = function () {
    var out = new glMatrix.ARRAY_TYPE(2);
    out[0] = 0;
    out[1] = 0;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.cross"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>cross (out, a, b)](#apidoc.element.gl-matrix.vec2.cross)
- description and source-code
```javascript
cross = function (out, a, b) {
    var z = a[0] * b[1] - a[1] * b[0];
    out[0] = out[1] = 0;
    out[2] = z;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.dist"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>dist (a, b)](#apidoc.element.gl-matrix.vec2.dist)
- description and source-code
```javascript
dist = function (a, b) {
    var x = b[0] - a[0],
        y = b[1] - a[1];
    return Math.sqrt(x*x + y*y);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.distance"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>distance (a, b)](#apidoc.element.gl-matrix.vec2.distance)
- description and source-code
```javascript
distance = function (a, b) {
    var x = b[0] - a[0],
        y = b[1] - a[1];
    return Math.sqrt(x*x + y*y);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.div"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>div (out, a, b)](#apidoc.element.gl-matrix.vec2.div)
- description and source-code
```javascript
div = function (out, a, b) {
    out[0] = a[0] / b[0];
    out[1] = a[1] / b[1];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.divide"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>divide (out, a, b)](#apidoc.element.gl-matrix.vec2.divide)
- description and source-code
```javascript
divide = function (out, a, b) {
    out[0] = a[0] / b[0];
    out[1] = a[1] / b[1];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.dot"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>dot (a, b)](#apidoc.element.gl-matrix.vec2.dot)
- description and source-code
```javascript
dot = function (a, b) {
    return a[0] * b[0] + a[1] * b[1];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.equals"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>equals (a, b)](#apidoc.element.gl-matrix.vec2.equals)
- description and source-code
```javascript
equals = function (a, b) {
    var a0 = a[0], a1 = a[1];
    var b0 = b[0], b1 = b[1];
    return (Math.abs(a0 - b0) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a0), Math.abs(b0)) &&
            Math.abs(a1 - b1) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a1), Math.abs(b1)));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.exactEquals"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>exactEquals (a, b)](#apidoc.element.gl-matrix.vec2.exactEquals)
- description and source-code
```javascript
exactEquals = function (a, b) {
    return a[0] === b[0] && a[1] === b[1];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.floor"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>floor (out, a)](#apidoc.element.gl-matrix.vec2.floor)
- description and source-code
```javascript
floor = function (out, a) {
    out[0] = Math.floor(a[0]);
    out[1] = Math.floor(a[1]);
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.forEach"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>forEach (a, stride, offset, count, fn, arg)](#apidoc.element.gl-matrix.vec2.forEach)
- description and source-code
```javascript
forEach = function (a, stride, offset, count, fn, arg) {
    var i, l;
    if(!stride) {
        stride = 2;
    }

    if(!offset) {
        offset = 0;
    }

    if(count) {
        l = Math.min((count * stride) + offset, a.length);
    } else {
        l = a.length;
    }

    for(i = offset; i < l; i += stride) {
        vec[0] = a[i]; vec[1] = a[i+1];
        fn(vec, vec, arg);
        a[i] = vec[0]; a[i+1] = vec[1];
    }

    return a;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.fromValues"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>fromValues (x, y)](#apidoc.element.gl-matrix.vec2.fromValues)
- description and source-code
```javascript
fromValues = function (x, y) {
    var out = new glMatrix.ARRAY_TYPE(2);
    out[0] = x;
    out[1] = y;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.inverse"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>inverse (out, a)](#apidoc.element.gl-matrix.vec2.inverse)
- description and source-code
```javascript
inverse = function (out, a) {
  out[0] = 1.0 / a[0];
  out[1] = 1.0 / a[1];
  return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.len"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>len (a)](#apidoc.element.gl-matrix.vec2.len)
- description and source-code
```javascript
len = function (a) {
    var x = a[0],
        y = a[1];
    return Math.sqrt(x*x + y*y);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.length"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>length (a)](#apidoc.element.gl-matrix.vec2.length)
- description and source-code
```javascript
length = function (a) {
    var x = a[0],
        y = a[1];
    return Math.sqrt(x*x + y*y);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.lerp"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>lerp (out, a, b, t)](#apidoc.element.gl-matrix.vec2.lerp)
- description and source-code
```javascript
lerp = function (out, a, b, t) {
    var ax = a[0],
        ay = a[1];
    out[0] = ax + t * (b[0] - ax);
    out[1] = ay + t * (b[1] - ay);
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.max"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>max (out, a, b)](#apidoc.element.gl-matrix.vec2.max)
- description and source-code
```javascript
max = function (out, a, b) {
    out[0] = Math.max(a[0], b[0]);
    out[1] = Math.max(a[1], b[1]);
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.min"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>min (out, a, b)](#apidoc.element.gl-matrix.vec2.min)
- description and source-code
```javascript
min = function (out, a, b) {
    out[0] = Math.min(a[0], b[0]);
    out[1] = Math.min(a[1], b[1]);
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.mul"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>mul (out, a, b)](#apidoc.element.gl-matrix.vec2.mul)
- description and source-code
```javascript
mul = function (out, a, b) {
    out[0] = a[0] * b[0];
    out[1] = a[1] * b[1];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.multiply"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>multiply (out, a, b)](#apidoc.element.gl-matrix.vec2.multiply)
- description and source-code
```javascript
multiply = function (out, a, b) {
    out[0] = a[0] * b[0];
    out[1] = a[1] * b[1];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.negate"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>negate (out, a)](#apidoc.element.gl-matrix.vec2.negate)
- description and source-code
```javascript
negate = function (out, a) {
    out[0] = -a[0];
    out[1] = -a[1];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.normalize"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>normalize (out, a)](#apidoc.element.gl-matrix.vec2.normalize)
- description and source-code
```javascript
normalize = function (out, a) {
    var x = a[0],
        y = a[1];
    var len = x*x + y*y;
    if (len > 0) {
        //TODO: evaluate use of glm_invsqrt here?
        len = 1 / Math.sqrt(len);
        out[0] = a[0] * len;
        out[1] = a[1] * len;
    }
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.random"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>random (out, scale)](#apidoc.element.gl-matrix.vec2.random)
- description and source-code
```javascript
random = function (out, scale) {
    scale = scale || 1.0;
    var r = glMatrix.RANDOM() * 2.0 * Math.PI;
    out[0] = Math.cos(r) * scale;
    out[1] = Math.sin(r) * scale;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.round"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>round (out, a)](#apidoc.element.gl-matrix.vec2.round)
- description and source-code
```javascript
round = function (out, a) {
    out[0] = Math.round(a[0]);
    out[1] = Math.round(a[1]);
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.scale"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>scale (out, a, b)](#apidoc.element.gl-matrix.vec2.scale)
- description and source-code
```javascript
scale = function (out, a, b) {
    out[0] = a[0] * b;
    out[1] = a[1] * b;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.scaleAndAdd"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>scaleAndAdd (out, a, b, scale)](#apidoc.element.gl-matrix.vec2.scaleAndAdd)
- description and source-code
```javascript
scaleAndAdd = function (out, a, b, scale) {
    out[0] = a[0] + (b[0] * scale);
    out[1] = a[1] + (b[1] * scale);
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.set"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>set (out, x, y)](#apidoc.element.gl-matrix.vec2.set)
- description and source-code
```javascript
set = function (out, x, y) {
    out[0] = x;
    out[1] = y;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.sqrDist"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>sqrDist (a, b)](#apidoc.element.gl-matrix.vec2.sqrDist)
- description and source-code
```javascript
sqrDist = function (a, b) {
    var x = b[0] - a[0],
        y = b[1] - a[1];
    return x*x + y*y;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.sqrLen"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>sqrLen (a)](#apidoc.element.gl-matrix.vec2.sqrLen)
- description and source-code
```javascript
sqrLen = function (a) {
    var x = a[0],
        y = a[1];
    return x*x + y*y;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.squaredDistance"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>squaredDistance (a, b)](#apidoc.element.gl-matrix.vec2.squaredDistance)
- description and source-code
```javascript
squaredDistance = function (a, b) {
    var x = b[0] - a[0],
        y = b[1] - a[1];
    return x*x + y*y;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.squaredLength"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>squaredLength (a)](#apidoc.element.gl-matrix.vec2.squaredLength)
- description and source-code
```javascript
squaredLength = function (a) {
    var x = a[0],
        y = a[1];
    return x*x + y*y;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.str"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>str (a)](#apidoc.element.gl-matrix.vec2.str)
- description and source-code
```javascript
str = function (a) {
    return 'vec2(' + a[0] + ', ' + a[1] + ')';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.sub"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>sub (out, a, b)](#apidoc.element.gl-matrix.vec2.sub)
- description and source-code
```javascript
sub = function (out, a, b) {
    out[0] = a[0] - b[0];
    out[1] = a[1] - b[1];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.subtract"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>subtract (out, a, b)](#apidoc.element.gl-matrix.vec2.subtract)
- description and source-code
```javascript
subtract = function (out, a, b) {
    out[0] = a[0] - b[0];
    out[1] = a[1] - b[1];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.transformMat2"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>transformMat2 (out, a, m)](#apidoc.element.gl-matrix.vec2.transformMat2)
- description and source-code
```javascript
transformMat2 = function (out, a, m) {
    var x = a[0],
        y = a[1];
    out[0] = m[0] * x + m[2] * y;
    out[1] = m[1] * x + m[3] * y;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.transformMat2d"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>transformMat2d (out, a, m)](#apidoc.element.gl-matrix.vec2.transformMat2d)
- description and source-code
```javascript
transformMat2d = function (out, a, m) {
    var x = a[0],
        y = a[1];
    out[0] = m[0] * x + m[2] * y + m[4];
    out[1] = m[1] * x + m[3] * y + m[5];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.transformMat3"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>transformMat3 (out, a, m)](#apidoc.element.gl-matrix.vec2.transformMat3)
- description and source-code
```javascript
transformMat3 = function (out, a, m) {
    var x = a[0],
        y = a[1];
    out[0] = m[0] * x + m[3] * y + m[6];
    out[1] = m[1] * x + m[4] * y + m[7];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec2.transformMat4"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec2.</span>transformMat4 (out, a, m)](#apidoc.element.gl-matrix.vec2.transformMat4)
- description and source-code
```javascript
transformMat4 = function (out, a, m) {
    var x = a[0],
        y = a[1];
    out[0] = m[0] * x + m[4] * y + m[12];
    out[1] = m[1] * x + m[5] * y + m[13];
    return out;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gl-matrix.vec3"></a>[module gl-matrix.vec3](#apidoc.module.gl-matrix.vec3)

#### <a name="apidoc.element.gl-matrix.vec3.add"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>add (out, a, b)](#apidoc.element.gl-matrix.vec3.add)
- description and source-code
```javascript
add = function (out, a, b) {
    out[0] = a[0] + b[0];
    out[1] = a[1] + b[1];
    out[2] = a[2] + b[2];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.angle"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>angle (a, b)](#apidoc.element.gl-matrix.vec3.angle)
- description and source-code
```javascript
angle = function (a, b) {

    var tempA = vec3.fromValues(a[0], a[1], a[2]);
    var tempB = vec3.fromValues(b[0], b[1], b[2]);

    vec3.normalize(tempA, tempA);
    vec3.normalize(tempB, tempB);

    var cosine = vec3.dot(tempA, tempB);

    if(cosine > 1.0){
        return 0;
    } else {
        return Math.acos(cosine);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.bezier"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>bezier (out, a, b, c, d, t)](#apidoc.element.gl-matrix.vec3.bezier)
- description and source-code
```javascript
bezier = function (out, a, b, c, d, t) {
  var inverseFactor = 1 - t,
      inverseFactorTimesTwo = inverseFactor * inverseFactor,
      factorTimes2 = t * t,
      factor1 = inverseFactorTimesTwo * inverseFactor,
      factor2 = 3 * t * inverseFactorTimesTwo,
      factor3 = 3 * factorTimes2 * inverseFactor,
      factor4 = factorTimes2 * t;

  out[0] = a[0] * factor1 + b[0] * factor2 + c[0] * factor3 + d[0] * factor4;
  out[1] = a[1] * factor1 + b[1] * factor2 + c[1] * factor3 + d[1] * factor4;
  out[2] = a[2] * factor1 + b[2] * factor2 + c[2] * factor3 + d[2] * factor4;

  return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.ceil"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>ceil (out, a)](#apidoc.element.gl-matrix.vec3.ceil)
- description and source-code
```javascript
ceil = function (out, a) {
    out[0] = Math.ceil(a[0]);
    out[1] = Math.ceil(a[1]);
    out[2] = Math.ceil(a[2]);
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.clone"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>clone (a)](#apidoc.element.gl-matrix.vec3.clone)
- description and source-code
```javascript
clone = function (a) {
    var out = new glMatrix.ARRAY_TYPE(3);
    out[0] = a[0];
    out[1] = a[1];
    out[2] = a[2];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.copy"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>copy (out, a)](#apidoc.element.gl-matrix.vec3.copy)
- description and source-code
```javascript
copy = function (out, a) {
    out[0] = a[0];
    out[1] = a[1];
    out[2] = a[2];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.create"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>create ()](#apidoc.element.gl-matrix.vec3.create)
- description and source-code
```javascript
create = function () {
    var out = new glMatrix.ARRAY_TYPE(3);
    out[0] = 0;
    out[1] = 0;
    out[2] = 0;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.cross"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>cross (out, a, b)](#apidoc.element.gl-matrix.vec3.cross)
- description and source-code
```javascript
cross = function (out, a, b) {
    var ax = a[0], ay = a[1], az = a[2],
        bx = b[0], by = b[1], bz = b[2];

    out[0] = ay * bz - az * by;
    out[1] = az * bx - ax * bz;
    out[2] = ax * by - ay * bx;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.dist"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>dist (a, b)](#apidoc.element.gl-matrix.vec3.dist)
- description and source-code
```javascript
dist = function (a, b) {
    var x = b[0] - a[0],
        y = b[1] - a[1],
        z = b[2] - a[2];
    return Math.sqrt(x*x + y*y + z*z);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.distance"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>distance (a, b)](#apidoc.element.gl-matrix.vec3.distance)
- description and source-code
```javascript
distance = function (a, b) {
    var x = b[0] - a[0],
        y = b[1] - a[1],
        z = b[2] - a[2];
    return Math.sqrt(x*x + y*y + z*z);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.div"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>div (out, a, b)](#apidoc.element.gl-matrix.vec3.div)
- description and source-code
```javascript
div = function (out, a, b) {
    out[0] = a[0] / b[0];
    out[1] = a[1] / b[1];
    out[2] = a[2] / b[2];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.divide"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>divide (out, a, b)](#apidoc.element.gl-matrix.vec3.divide)
- description and source-code
```javascript
divide = function (out, a, b) {
    out[0] = a[0] / b[0];
    out[1] = a[1] / b[1];
    out[2] = a[2] / b[2];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.dot"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>dot (a, b)](#apidoc.element.gl-matrix.vec3.dot)
- description and source-code
```javascript
dot = function (a, b) {
    return a[0] * b[0] + a[1] * b[1] + a[2] * b[2];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.equals"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>equals (a, b)](#apidoc.element.gl-matrix.vec3.equals)
- description and source-code
```javascript
equals = function (a, b) {
    var a0 = a[0], a1 = a[1], a2 = a[2];
    var b0 = b[0], b1 = b[1], b2 = b[2];
    return (Math.abs(a0 - b0) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a0), Math.abs(b0)) &&
            Math.abs(a1 - b1) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a1), Math.abs(b1)) &&
            Math.abs(a2 - b2) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a2), Math.abs(b2)));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.exactEquals"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>exactEquals (a, b)](#apidoc.element.gl-matrix.vec3.exactEquals)
- description and source-code
```javascript
exactEquals = function (a, b) {
    return a[0] === b[0] && a[1] === b[1] && a[2] === b[2];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.floor"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>floor (out, a)](#apidoc.element.gl-matrix.vec3.floor)
- description and source-code
```javascript
floor = function (out, a) {
    out[0] = Math.floor(a[0]);
    out[1] = Math.floor(a[1]);
    out[2] = Math.floor(a[2]);
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.forEach"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>forEach (a, stride, offset, count, fn, arg)](#apidoc.element.gl-matrix.vec3.forEach)
- description and source-code
```javascript
forEach = function (a, stride, offset, count, fn, arg) {
    var i, l;
    if(!stride) {
        stride = 3;
    }

    if(!offset) {
        offset = 0;
    }

    if(count) {
        l = Math.min((count * stride) + offset, a.length);
    } else {
        l = a.length;
    }

    for(i = offset; i < l; i += stride) {
        vec[0] = a[i]; vec[1] = a[i+1]; vec[2] = a[i+2];
        fn(vec, vec, arg);
        a[i] = vec[0]; a[i+1] = vec[1]; a[i+2] = vec[2];
    }

    return a;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.fromValues"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>fromValues (x, y, z)](#apidoc.element.gl-matrix.vec3.fromValues)
- description and source-code
```javascript
fromValues = function (x, y, z) {
    var out = new glMatrix.ARRAY_TYPE(3);
    out[0] = x;
    out[1] = y;
    out[2] = z;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.hermite"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>hermite (out, a, b, c, d, t)](#apidoc.element.gl-matrix.vec3.hermite)
- description and source-code
```javascript
hermite = function (out, a, b, c, d, t) {
  var factorTimes2 = t * t,
      factor1 = factorTimes2 * (2 * t - 3) + 1,
      factor2 = factorTimes2 * (t - 2) + t,
      factor3 = factorTimes2 * (t - 1),
      factor4 = factorTimes2 * (3 - 2 * t);

  out[0] = a[0] * factor1 + b[0] * factor2 + c[0] * factor3 + d[0] * factor4;
  out[1] = a[1] * factor1 + b[1] * factor2 + c[1] * factor3 + d[1] * factor4;
  out[2] = a[2] * factor1 + b[2] * factor2 + c[2] * factor3 + d[2] * factor4;

  return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.inverse"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>inverse (out, a)](#apidoc.element.gl-matrix.vec3.inverse)
- description and source-code
```javascript
inverse = function (out, a) {
  out[0] = 1.0 / a[0];
  out[1] = 1.0 / a[1];
  out[2] = 1.0 / a[2];
  return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.len"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>len (a)](#apidoc.element.gl-matrix.vec3.len)
- description and source-code
```javascript
len = function (a) {
    var x = a[0],
        y = a[1],
        z = a[2];
    return Math.sqrt(x*x + y*y + z*z);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.length"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>length (a)](#apidoc.element.gl-matrix.vec3.length)
- description and source-code
```javascript
length = function (a) {
    var x = a[0],
        y = a[1],
        z = a[2];
    return Math.sqrt(x*x + y*y + z*z);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.lerp"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>lerp (out, a, b, t)](#apidoc.element.gl-matrix.vec3.lerp)
- description and source-code
```javascript
lerp = function (out, a, b, t) {
    var ax = a[0],
        ay = a[1],
        az = a[2];
    out[0] = ax + t * (b[0] - ax);
    out[1] = ay + t * (b[1] - ay);
    out[2] = az + t * (b[2] - az);
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.max"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>max (out, a, b)](#apidoc.element.gl-matrix.vec3.max)
- description and source-code
```javascript
max = function (out, a, b) {
    out[0] = Math.max(a[0], b[0]);
    out[1] = Math.max(a[1], b[1]);
    out[2] = Math.max(a[2], b[2]);
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.min"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>min (out, a, b)](#apidoc.element.gl-matrix.vec3.min)
- description and source-code
```javascript
min = function (out, a, b) {
    out[0] = Math.min(a[0], b[0]);
    out[1] = Math.min(a[1], b[1]);
    out[2] = Math.min(a[2], b[2]);
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.mul"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>mul (out, a, b)](#apidoc.element.gl-matrix.vec3.mul)
- description and source-code
```javascript
mul = function (out, a, b) {
    out[0] = a[0] * b[0];
    out[1] = a[1] * b[1];
    out[2] = a[2] * b[2];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.multiply"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>multiply (out, a, b)](#apidoc.element.gl-matrix.vec3.multiply)
- description and source-code
```javascript
multiply = function (out, a, b) {
    out[0] = a[0] * b[0];
    out[1] = a[1] * b[1];
    out[2] = a[2] * b[2];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.negate"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>negate (out, a)](#apidoc.element.gl-matrix.vec3.negate)
- description and source-code
```javascript
negate = function (out, a) {
    out[0] = -a[0];
    out[1] = -a[1];
    out[2] = -a[2];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.normalize"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>normalize (out, a)](#apidoc.element.gl-matrix.vec3.normalize)
- description and source-code
```javascript
normalize = function (out, a) {
    var x = a[0],
        y = a[1],
        z = a[2];
    var len = x*x + y*y + z*z;
    if (len > 0) {
        //TODO: evaluate use of glm_invsqrt here?
        len = 1 / Math.sqrt(len);
        out[0] = a[0] * len;
        out[1] = a[1] * len;
        out[2] = a[2] * len;
    }
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.random"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>random (out, scale)](#apidoc.element.gl-matrix.vec3.random)
- description and source-code
```javascript
random = function (out, scale) {
    scale = scale || 1.0;

    var r = glMatrix.RANDOM() * 2.0 * Math.PI;
    var z = (glMatrix.RANDOM() * 2.0) - 1.0;
    var zScale = Math.sqrt(1.0-z*z) * scale;

    out[0] = Math.cos(r) * zScale;
    out[1] = Math.sin(r) * zScale;
    out[2] = z * scale;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.rotateX"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>rotateX (out, a, b, c)](#apidoc.element.gl-matrix.vec3.rotateX)
- description and source-code
```javascript
rotateX = function (out, a, b, c){
   var p = [], r=[];
	  //Translate point to the origin
	  p[0] = a[0] - b[0];
	  p[1] = a[1] - b[1];
  	p[2] = a[2] - b[2];

	  //perform rotation
	  r[0] = p[0];
	  r[1] = p[1]*Math.cos(c) - p[2]*Math.sin(c);
	  r[2] = p[1]*Math.sin(c) + p[2]*Math.cos(c);

	  //translate to correct position
	  out[0] = r[0] + b[0];
	  out[1] = r[1] + b[1];
	  out[2] = r[2] + b[2];

  	return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.rotateY"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>rotateY (out, a, b, c)](#apidoc.element.gl-matrix.vec3.rotateY)
- description and source-code
```javascript
rotateY = function (out, a, b, c){
  	var p = [], r=[];
  	//Translate point to the origin
  	p[0] = a[0] - b[0];
  	p[1] = a[1] - b[1];
  	p[2] = a[2] - b[2];

  	//perform rotation
  	r[0] = p[2]*Math.sin(c) + p[0]*Math.cos(c);
  	r[1] = p[1];
  	r[2] = p[2]*Math.cos(c) - p[0]*Math.sin(c);

  	//translate to correct position
  	out[0] = r[0] + b[0];
  	out[1] = r[1] + b[1];
  	out[2] = r[2] + b[2];

  	return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.rotateZ"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>rotateZ (out, a, b, c)](#apidoc.element.gl-matrix.vec3.rotateZ)
- description and source-code
```javascript
rotateZ = function (out, a, b, c){
  	var p = [], r=[];
  	//Translate point to the origin
  	p[0] = a[0] - b[0];
  	p[1] = a[1] - b[1];
  	p[2] = a[2] - b[2];

  	//perform rotation
  	r[0] = p[0]*Math.cos(c) - p[1]*Math.sin(c);
  	r[1] = p[0]*Math.sin(c) + p[1]*Math.cos(c);
  	r[2] = p[2];

  	//translate to correct position
  	out[0] = r[0] + b[0];
  	out[1] = r[1] + b[1];
  	out[2] = r[2] + b[2];

  	return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.round"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>round (out, a)](#apidoc.element.gl-matrix.vec3.round)
- description and source-code
```javascript
round = function (out, a) {
    out[0] = Math.round(a[0]);
    out[1] = Math.round(a[1]);
    out[2] = Math.round(a[2]);
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.scale"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>scale (out, a, b)](#apidoc.element.gl-matrix.vec3.scale)
- description and source-code
```javascript
scale = function (out, a, b) {
    out[0] = a[0] * b;
    out[1] = a[1] * b;
    out[2] = a[2] * b;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.scaleAndAdd"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>scaleAndAdd (out, a, b, scale)](#apidoc.element.gl-matrix.vec3.scaleAndAdd)
- description and source-code
```javascript
scaleAndAdd = function (out, a, b, scale) {
    out[0] = a[0] + (b[0] * scale);
    out[1] = a[1] + (b[1] * scale);
    out[2] = a[2] + (b[2] * scale);
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.set"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>set (out, x, y, z)](#apidoc.element.gl-matrix.vec3.set)
- description and source-code
```javascript
set = function (out, x, y, z) {
    out[0] = x;
    out[1] = y;
    out[2] = z;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.sqrDist"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>sqrDist (a, b)](#apidoc.element.gl-matrix.vec3.sqrDist)
- description and source-code
```javascript
sqrDist = function (a, b) {
    var x = b[0] - a[0],
        y = b[1] - a[1],
        z = b[2] - a[2];
    return x*x + y*y + z*z;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.sqrLen"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>sqrLen (a)](#apidoc.element.gl-matrix.vec3.sqrLen)
- description and source-code
```javascript
sqrLen = function (a) {
    var x = a[0],
        y = a[1],
        z = a[2];
    return x*x + y*y + z*z;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.squaredDistance"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>squaredDistance (a, b)](#apidoc.element.gl-matrix.vec3.squaredDistance)
- description and source-code
```javascript
squaredDistance = function (a, b) {
    var x = b[0] - a[0],
        y = b[1] - a[1],
        z = b[2] - a[2];
    return x*x + y*y + z*z;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.squaredLength"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>squaredLength (a)](#apidoc.element.gl-matrix.vec3.squaredLength)
- description and source-code
```javascript
squaredLength = function (a) {
    var x = a[0],
        y = a[1],
        z = a[2];
    return x*x + y*y + z*z;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.str"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>str (a)](#apidoc.element.gl-matrix.vec3.str)
- description and source-code
```javascript
str = function (a) {
    return 'vec3(' + a[0] + ', ' + a[1] + ', ' + a[2] + ')';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.sub"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>sub (out, a, b)](#apidoc.element.gl-matrix.vec3.sub)
- description and source-code
```javascript
sub = function (out, a, b) {
    out[0] = a[0] - b[0];
    out[1] = a[1] - b[1];
    out[2] = a[2] - b[2];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.subtract"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>subtract (out, a, b)](#apidoc.element.gl-matrix.vec3.subtract)
- description and source-code
```javascript
subtract = function (out, a, b) {
    out[0] = a[0] - b[0];
    out[1] = a[1] - b[1];
    out[2] = a[2] - b[2];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.transformMat3"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>transformMat3 (out, a, m)](#apidoc.element.gl-matrix.vec3.transformMat3)
- description and source-code
```javascript
transformMat3 = function (out, a, m) {
    var x = a[0], y = a[1], z = a[2];
    out[0] = x * m[0] + y * m[3] + z * m[6];
    out[1] = x * m[1] + y * m[4] + z * m[7];
    out[2] = x * m[2] + y * m[5] + z * m[8];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.transformMat4"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>transformMat4 (out, a, m)](#apidoc.element.gl-matrix.vec3.transformMat4)
- description and source-code
```javascript
transformMat4 = function (out, a, m) {
    var x = a[0], y = a[1], z = a[2],
        w = m[3] * x + m[7] * y + m[11] * z + m[15];
    w = w || 1.0;
    out[0] = (m[0] * x + m[4] * y + m[8] * z + m[12]) / w;
    out[1] = (m[1] * x + m[5] * y + m[9] * z + m[13]) / w;
    out[2] = (m[2] * x + m[6] * y + m[10] * z + m[14]) / w;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec3.transformQuat"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec3.</span>transformQuat (out, a, q)](#apidoc.element.gl-matrix.vec3.transformQuat)
- description and source-code
```javascript
transformQuat = function (out, a, q) {
    // benchmarks: http://jsperf.com/quaternion-transform-vec3-implementations

    var x = a[0], y = a[1], z = a[2],
        qx = q[0], qy = q[1], qz = q[2], qw = q[3],

        // calculate quat * vec
        ix = qw * x + qy * z - qz * y,
        iy = qw * y + qz * x - qx * z,
        iz = qw * z + qx * y - qy * x,
        iw = -qx * x - qy * y - qz * z;

    // calculate result * inverse quat
    out[0] = ix * qw + iw * -qx + iy * -qz - iz * -qy;
    out[1] = iy * qw + iw * -qy + iz * -qx - ix * -qz;
    out[2] = iz * qw + iw * -qz + ix * -qy - iy * -qx;
    return out;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gl-matrix.vec4"></a>[module gl-matrix.vec4](#apidoc.module.gl-matrix.vec4)

#### <a name="apidoc.element.gl-matrix.vec4.add"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>add (out, a, b)](#apidoc.element.gl-matrix.vec4.add)
- description and source-code
```javascript
add = function (out, a, b) {
    out[0] = a[0] + b[0];
    out[1] = a[1] + b[1];
    out[2] = a[2] + b[2];
    out[3] = a[3] + b[3];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec4.ceil"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>ceil (out, a)](#apidoc.element.gl-matrix.vec4.ceil)
- description and source-code
```javascript
ceil = function (out, a) {
    out[0] = Math.ceil(a[0]);
    out[1] = Math.ceil(a[1]);
    out[2] = Math.ceil(a[2]);
    out[3] = Math.ceil(a[3]);
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec4.clone"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>clone (a)](#apidoc.element.gl-matrix.vec4.clone)
- description and source-code
```javascript
clone = function (a) {
    var out = new glMatrix.ARRAY_TYPE(4);
    out[0] = a[0];
    out[1] = a[1];
    out[2] = a[2];
    out[3] = a[3];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec4.copy"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>copy (out, a)](#apidoc.element.gl-matrix.vec4.copy)
- description and source-code
```javascript
copy = function (out, a) {
    out[0] = a[0];
    out[1] = a[1];
    out[2] = a[2];
    out[3] = a[3];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec4.create"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>create ()](#apidoc.element.gl-matrix.vec4.create)
- description and source-code
```javascript
create = function () {
    var out = new glMatrix.ARRAY_TYPE(4);
    out[0] = 0;
    out[1] = 0;
    out[2] = 0;
    out[3] = 0;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec4.dist"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>dist (a, b)](#apidoc.element.gl-matrix.vec4.dist)
- description and source-code
```javascript
dist = function (a, b) {
    var x = b[0] - a[0],
        y = b[1] - a[1],
        z = b[2] - a[2],
        w = b[3] - a[3];
    return Math.sqrt(x*x + y*y + z*z + w*w);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec4.distance"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>distance (a, b)](#apidoc.element.gl-matrix.vec4.distance)
- description and source-code
```javascript
distance = function (a, b) {
    var x = b[0] - a[0],
        y = b[1] - a[1],
        z = b[2] - a[2],
        w = b[3] - a[3];
    return Math.sqrt(x*x + y*y + z*z + w*w);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec4.div"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>div (out, a, b)](#apidoc.element.gl-matrix.vec4.div)
- description and source-code
```javascript
div = function (out, a, b) {
    out[0] = a[0] / b[0];
    out[1] = a[1] / b[1];
    out[2] = a[2] / b[2];
    out[3] = a[3] / b[3];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec4.divide"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>divide (out, a, b)](#apidoc.element.gl-matrix.vec4.divide)
- description and source-code
```javascript
divide = function (out, a, b) {
    out[0] = a[0] / b[0];
    out[1] = a[1] / b[1];
    out[2] = a[2] / b[2];
    out[3] = a[3] / b[3];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec4.dot"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>dot (a, b)](#apidoc.element.gl-matrix.vec4.dot)
- description and source-code
```javascript
dot = function (a, b) {
    return a[0] * b[0] + a[1] * b[1] + a[2] * b[2] + a[3] * b[3];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec4.equals"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>equals (a, b)](#apidoc.element.gl-matrix.vec4.equals)
- description and source-code
```javascript
equals = function (a, b) {
    var a0 = a[0], a1 = a[1], a2 = a[2], a3 = a[3];
    var b0 = b[0], b1 = b[1], b2 = b[2], b3 = b[3];
    return (Math.abs(a0 - b0) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a0), Math.abs(b0)) &&
            Math.abs(a1 - b1) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a1), Math.abs(b1)) &&
            Math.abs(a2 - b2) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a2), Math.abs(b2)) &&
            Math.abs(a3 - b3) <= glMatrix.EPSILON*Math.max(1.0, Math.abs(a3), Math.abs(b3)));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec4.exactEquals"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>exactEquals (a, b)](#apidoc.element.gl-matrix.vec4.exactEquals)
- description and source-code
```javascript
exactEquals = function (a, b) {
    return a[0] === b[0] && a[1] === b[1] && a[2] === b[2] && a[3] === b[3];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec4.floor"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>floor (out, a)](#apidoc.element.gl-matrix.vec4.floor)
- description and source-code
```javascript
floor = function (out, a) {
    out[0] = Math.floor(a[0]);
    out[1] = Math.floor(a[1]);
    out[2] = Math.floor(a[2]);
    out[3] = Math.floor(a[3]);
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec4.forEach"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>forEach (a, stride, offset, count, fn, arg)](#apidoc.element.gl-matrix.vec4.forEach)
- description and source-code
```javascript
forEach = function (a, stride, offset, count, fn, arg) {
    var i, l;
    if(!stride) {
        stride = 4;
    }

    if(!offset) {
        offset = 0;
    }

    if(count) {
        l = Math.min((count * stride) + offset, a.length);
    } else {
        l = a.length;
    }

    for(i = offset; i < l; i += stride) {
        vec[0] = a[i]; vec[1] = a[i+1]; vec[2] = a[i+2]; vec[3] = a[i+3];
        fn(vec, vec, arg);
        a[i] = vec[0]; a[i+1] = vec[1]; a[i+2] = vec[2]; a[i+3] = vec[3];
    }

    return a;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec4.fromValues"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>fromValues (x, y, z, w)](#apidoc.element.gl-matrix.vec4.fromValues)
- description and source-code
```javascript
fromValues = function (x, y, z, w) {
    var out = new glMatrix.ARRAY_TYPE(4);
    out[0] = x;
    out[1] = y;
    out[2] = z;
    out[3] = w;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec4.inverse"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>inverse (out, a)](#apidoc.element.gl-matrix.vec4.inverse)
- description and source-code
```javascript
inverse = function (out, a) {
  out[0] = 1.0 / a[0];
  out[1] = 1.0 / a[1];
  out[2] = 1.0 / a[2];
  out[3] = 1.0 / a[3];
  return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec4.len"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>len (a)](#apidoc.element.gl-matrix.vec4.len)
- description and source-code
```javascript
len = function (a) {
    var x = a[0],
        y = a[1],
        z = a[2],
        w = a[3];
    return Math.sqrt(x*x + y*y + z*z + w*w);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec4.length"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>length (a)](#apidoc.element.gl-matrix.vec4.length)
- description and source-code
```javascript
length = function (a) {
    var x = a[0],
        y = a[1],
        z = a[2],
        w = a[3];
    return Math.sqrt(x*x + y*y + z*z + w*w);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec4.lerp"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>lerp (out, a, b, t)](#apidoc.element.gl-matrix.vec4.lerp)
- description and source-code
```javascript
lerp = function (out, a, b, t) {
    var ax = a[0],
        ay = a[1],
        az = a[2],
        aw = a[3];
    out[0] = ax + t * (b[0] - ax);
    out[1] = ay + t * (b[1] - ay);
    out[2] = az + t * (b[2] - az);
    out[3] = aw + t * (b[3] - aw);
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec4.max"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>max (out, a, b)](#apidoc.element.gl-matrix.vec4.max)
- description and source-code
```javascript
max = function (out, a, b) {
    out[0] = Math.max(a[0], b[0]);
    out[1] = Math.max(a[1], b[1]);
    out[2] = Math.max(a[2], b[2]);
    out[3] = Math.max(a[3], b[3]);
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec4.min"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>min (out, a, b)](#apidoc.element.gl-matrix.vec4.min)
- description and source-code
```javascript
min = function (out, a, b) {
    out[0] = Math.min(a[0], b[0]);
    out[1] = Math.min(a[1], b[1]);
    out[2] = Math.min(a[2], b[2]);
    out[3] = Math.min(a[3], b[3]);
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec4.mul"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>mul (out, a, b)](#apidoc.element.gl-matrix.vec4.mul)
- description and source-code
```javascript
mul = function (out, a, b) {
    out[0] = a[0] * b[0];
    out[1] = a[1] * b[1];
    out[2] = a[2] * b[2];
    out[3] = a[3] * b[3];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec4.multiply"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>multiply (out, a, b)](#apidoc.element.gl-matrix.vec4.multiply)
- description and source-code
```javascript
multiply = function (out, a, b) {
    out[0] = a[0] * b[0];
    out[1] = a[1] * b[1];
    out[2] = a[2] * b[2];
    out[3] = a[3] * b[3];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec4.negate"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>negate (out, a)](#apidoc.element.gl-matrix.vec4.negate)
- description and source-code
```javascript
negate = function (out, a) {
    out[0] = -a[0];
    out[1] = -a[1];
    out[2] = -a[2];
    out[3] = -a[3];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec4.normalize"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>normalize (out, a)](#apidoc.element.gl-matrix.vec4.normalize)
- description and source-code
```javascript
normalize = function (out, a) {
    var x = a[0],
        y = a[1],
        z = a[2],
        w = a[3];
    var len = x*x + y*y + z*z + w*w;
    if (len > 0) {
        len = 1 / Math.sqrt(len);
        out[0] = x * len;
        out[1] = y * len;
        out[2] = z * len;
        out[3] = w * len;
    }
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec4.random"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>random (out, scale)](#apidoc.element.gl-matrix.vec4.random)
- description and source-code
```javascript
random = function (out, scale) {
    scale = scale || 1.0;

    //TODO: This is a pretty awful way of doing this. Find something better.
    out[0] = glMatrix.RANDOM();
    out[1] = glMatrix.RANDOM();
    out[2] = glMatrix.RANDOM();
    out[3] = glMatrix.RANDOM();
    vec4.normalize(out, out);
    vec4.scale(out, out, scale);
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec4.round"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>round (out, a)](#apidoc.element.gl-matrix.vec4.round)
- description and source-code
```javascript
round = function (out, a) {
    out[0] = Math.round(a[0]);
    out[1] = Math.round(a[1]);
    out[2] = Math.round(a[2]);
    out[3] = Math.round(a[3]);
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec4.scale"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>scale (out, a, b)](#apidoc.element.gl-matrix.vec4.scale)
- description and source-code
```javascript
scale = function (out, a, b) {
    out[0] = a[0] * b;
    out[1] = a[1] * b;
    out[2] = a[2] * b;
    out[3] = a[3] * b;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec4.scaleAndAdd"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>scaleAndAdd (out, a, b, scale)](#apidoc.element.gl-matrix.vec4.scaleAndAdd)
- description and source-code
```javascript
scaleAndAdd = function (out, a, b, scale) {
    out[0] = a[0] + (b[0] * scale);
    out[1] = a[1] + (b[1] * scale);
    out[2] = a[2] + (b[2] * scale);
    out[3] = a[3] + (b[3] * scale);
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec4.set"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>set (out, x, y, z, w)](#apidoc.element.gl-matrix.vec4.set)
- description and source-code
```javascript
set = function (out, x, y, z, w) {
    out[0] = x;
    out[1] = y;
    out[2] = z;
    out[3] = w;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec4.sqrDist"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>sqrDist (a, b)](#apidoc.element.gl-matrix.vec4.sqrDist)
- description and source-code
```javascript
sqrDist = function (a, b) {
    var x = b[0] - a[0],
        y = b[1] - a[1],
        z = b[2] - a[2],
        w = b[3] - a[3];
    return x*x + y*y + z*z + w*w;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec4.sqrLen"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>sqrLen (a)](#apidoc.element.gl-matrix.vec4.sqrLen)
- description and source-code
```javascript
sqrLen = function (a) {
    var x = a[0],
        y = a[1],
        z = a[2],
        w = a[3];
    return x*x + y*y + z*z + w*w;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec4.squaredDistance"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>squaredDistance (a, b)](#apidoc.element.gl-matrix.vec4.squaredDistance)
- description and source-code
```javascript
squaredDistance = function (a, b) {
    var x = b[0] - a[0],
        y = b[1] - a[1],
        z = b[2] - a[2],
        w = b[3] - a[3];
    return x*x + y*y + z*z + w*w;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec4.squaredLength"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>squaredLength (a)](#apidoc.element.gl-matrix.vec4.squaredLength)
- description and source-code
```javascript
squaredLength = function (a) {
    var x = a[0],
        y = a[1],
        z = a[2],
        w = a[3];
    return x*x + y*y + z*z + w*w;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec4.str"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>str (a)](#apidoc.element.gl-matrix.vec4.str)
- description and source-code
```javascript
str = function (a) {
    return 'vec4(' + a[0] + ', ' + a[1] + ', ' + a[2] + ', ' + a[3] + ')';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec4.sub"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>sub (out, a, b)](#apidoc.element.gl-matrix.vec4.sub)
- description and source-code
```javascript
sub = function (out, a, b) {
    out[0] = a[0] - b[0];
    out[1] = a[1] - b[1];
    out[2] = a[2] - b[2];
    out[3] = a[3] - b[3];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec4.subtract"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>subtract (out, a, b)](#apidoc.element.gl-matrix.vec4.subtract)
- description and source-code
```javascript
subtract = function (out, a, b) {
    out[0] = a[0] - b[0];
    out[1] = a[1] - b[1];
    out[2] = a[2] - b[2];
    out[3] = a[3] - b[3];
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec4.transformMat4"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>transformMat4 (out, a, m)](#apidoc.element.gl-matrix.vec4.transformMat4)
- description and source-code
```javascript
transformMat4 = function (out, a, m) {
    var x = a[0], y = a[1], z = a[2], w = a[3];
    out[0] = m[0] * x + m[4] * y + m[8] * z + m[12] * w;
    out[1] = m[1] * x + m[5] * y + m[9] * z + m[13] * w;
    out[2] = m[2] * x + m[6] * y + m[10] * z + m[14] * w;
    out[3] = m[3] * x + m[7] * y + m[11] * z + m[15] * w;
    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gl-matrix.vec4.transformQuat"></a>[function <span class="apidocSignatureSpan">gl-matrix.vec4.</span>transformQuat (out, a, q)](#apidoc.element.gl-matrix.vec4.transformQuat)
- description and source-code
```javascript
transformQuat = function (out, a, q) {
    var x = a[0], y = a[1], z = a[2],
        qx = q[0], qy = q[1], qz = q[2], qw = q[3],

        // calculate quat * vec
        ix = qw * x + qy * z - qz * y,
        iy = qw * y + qz * x - qx * z,
        iz = qw * z + qx * y - qy * x,
        iw = -qx * x - qy * y - qz * z;

    // calculate result * inverse quat
    out[0] = ix * qw + iw * -qx + iy * -qz - iz * -qy;
    out[1] = iy * qw + iw * -qy + iz * -qx - ix * -qz;
    out[2] = iz * qw + iw * -qz + ix * -qy - iy * -qx;
    out[3] = a[3];
    return out;
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
