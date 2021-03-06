#### 0.27.2 (2019-05-12)

##### Chores

* **deps:**  force latest version & audit fix ([65982a7a](https://github.com/lykmapipo/mongoose-rest-actions/commit/65982a7a9f4e001c253025cb27285674e871740c))

#### 0.27.1 (2019-05-12)

##### Chores

* **deps:**  force latest version & audit fix ([786394b2](https://github.com/lykmapipo/mongoose-rest-actions/commit/786394b2bbc4f0000888d88f223dc6143a7ecf7a))

#### 0.27.0 (2019-05-10)

##### Chores

* **deps:**
  *  force latest version & audit fix ([4aa95fff](https://github.com/lykmapipo/mongoose-rest-actions/commit/4aa95fffb9460ab2c25609740c84c1cc5d07d644))
  *  force latest version & audit fix ([f759d9b3](https://github.com/lykmapipo/mongoose-rest-actions/commit/f759d9b30c25ec33cb125b48ea5443c1d5a3522f))

##### New Features

* **get-by-id:**  add before and after getById static hooks ([279850d7](https://github.com/lykmapipo/mongoose-rest-actions/commit/279850d721281e53b12d24f3184da736886ff440))
*  ignore _id & updatedAt updates on instance.put method ([5a645383](https://github.com/lykmapipo/mongoose-rest-actions/commit/5a6453831b6b15828ac901bb92ffc2a353b60b83))
*  ignore instances on put static method ([85b08458](https://github.com/lykmapipo/mongoose-rest-actions/commit/85b084581688ae53906a886fc745a4f1cdf94fdc))
*  add hasMore flag or list responses ([026d075f](https://github.com/lykmapipo/mongoose-rest-actions/commit/026d075f37b820162e3404a11acc671f12b8b26e))

##### Other Changes

* **get:**  use orFail when getById ([79616ac3](https://github.com/lykmapipo/mongoose-rest-actions/commit/79616ac3445ec2302200e2d92068a15c7bef4325))

##### Refactors

*  ensure error status & pre/post hooks executions ([c83496cf](https://github.com/lykmapipo/mongoose-rest-actions/commit/c83496cf2378ecdab6b93b449967400d2141708c))
* **patch:**  support instance & refs as updates ([034b2f97](https://github.com/lykmapipo/mongoose-rest-actions/commit/034b2f97235a2d49df7378a162f3224d9c6011a1))
* **put:**  honour instances as updates ([cb7e5106](https://github.com/lykmapipo/mongoose-rest-actions/commit/cb7e5106046ae3c900eff8f2ff515d068764e068))
* **static-put:**  use orFail when finf existing ([6539b77d](https://github.com/lykmapipo/mongoose-rest-actions/commit/6539b77d9b2a3e65cc33378c99eca382d4f38ae1))

##### Code Style Changes

*  collapse jsdocs exceed 80 ruler ([7df13972](https://github.com/lykmapipo/mongoose-rest-actions/commit/7df139729b2773813ea4d32785680a66735b27fa))

##### Tests

*  spy invocation of exec on put and patch ([8ef6806f](https://github.com/lykmapipo/mongoose-rest-actions/commit/8ef6806f896fe1ba12aadd4330c87cf36555d053))
*  fix put instances using model static put ([56cebb68](https://github.com/lykmapipo/mongoose-rest-actions/commit/56cebb682bc6ef5208fbb6e8666d6fe32fc9e59f))

#### 0.26.0 (2019-05-05)

##### Chores

* **deps:**  force latest versions & audit fixes ([7825170b](https://github.com/lykmapipo/mongoose-rest-actions/commit/7825170b0c729b7abcc76187a73b88ab2fd328f5))

##### New Features

*  allow static soft delete option ([20952127](https://github.com/lykmapipo/mongoose-rest-actions/commit/20952127b42c23cac3f71fb01c39d2da58765865))
*  allow instance soft delete option ([22978ee0](https://github.com/lykmapipo/mongoose-rest-actions/commit/22978ee09ff0f56a4a8d5bc8f9ba2594cefeb835))

##### Refactors

* **plugin:**  reorder rest actions plugin on schema ([d0844323](https://github.com/lykmapipo/mongoose-rest-actions/commit/d0844323879b7342c429ee87638e694b6738de46))

#### 0.25.4 (2019-05-01)

##### Chores

* **deps:**  force latest version & audit fix ([f96a3587](https://github.com/lykmapipo/mongoose-rest-actions/commit/f96a358785a1489c6fd9832128990022e1d3ebb8))

#### 0.25.3 (2019-05-01)

##### Chores

* **ci:**  force latest nodejs ([c4f357ed](https://github.com/lykmapipo/mongoose-rest-actions/commit/c4f357ed90a654a8239f5b13c4a89a83890b8350))
* **.npmrc:**  prevent npm version to commit and tag version ([3a995d1b](https://github.com/lykmapipo/mongoose-rest-actions/commit/3a995d1babf0c3b4f61aa0eb27ba04d6003ef474))
* **deps:**  force latest version & audit fix ([eba69bae](https://github.com/lykmapipo/mongoose-rest-actions/commit/eba69bae285034ac10d5bdb100c84006d57fc2de))

#### 0.25.2 (2019-04-27)

##### Chores

* **dependencies:**
  *  force latest versions ([335e5ca3](https://github.com/lykmapipo/mongoose-rest-actions/commit/335e5ca3780af9174fbf4706263883d6dee870b5))
  *  remove unused ([c9ba3709](https://github.com/lykmapipo/mongoose-rest-actions/commit/c9ba3709cb6a49341d395cda8207f16608e7e763))
  *  force latest versions ([4c72c0b0](https://github.com/lykmapipo/mongoose-rest-actions/commit/4c72c0b0a45d5924e6c27e93b164c28f89b81c69))
* **release:**  generate latest changelog & bump to v0.25.1 ([7c6b81c7](https://github.com/lykmapipo/mongoose-rest-actions/commit/7c6b81c724e2741f4d8d09f37a97b078653edb63))
*  fix dependency security vulnerability ([c5370860](https://github.com/lykmapipo/mongoose-rest-actions/commit/c5370860145ae1c91b6cf7e988b9e0e8f1b40e16))

##### Code Style Changes

*  update JSDoc and fix typos ([ae7e79c6](https://github.com/lykmapipo/mongoose-rest-actions/commit/ae7e79c60917c9ec49c47e9ed26b78f9493eb8e2))

#### 0.25.1 (2019-04-24)

##### Chores

* **dependencies:**
  *  remove unused ([c9ba3709](https://github.com/lykmapipo/mongoose-rest-actions/commit/c9ba3709cb6a49341d395cda8207f16608e7e763))
  *  force latest versions ([4c72c0b0](https://github.com/lykmapipo/mongoose-rest-actions/commit/4c72c0b0a45d5924e6c27e93b164c28f89b81c69))

#### 0.25.0 (2019-04-21)

##### Chores

*  force latest dependencies ([edb06ce0](https://github.com/lykmapipo/mongoose-rest-actions/commit/edb06ce07e45b3c4d68457e17600efdc339be981))
*  fotce latest node in travis ([a349a5a6](https://github.com/lykmapipo/mongoose-rest-actions/commit/a349a5a613e45e3610b9efc9434c4a0b5314b415))
*  force latest dependencies ([51241039](https://github.com/lykmapipo/mongoose-rest-actions/commit/51241039da2c44e121135a18b1bfab2be43e69f7))

##### Refactors

* **post:**  use instance save & improve specs ([6ba006c5](https://github.com/lykmapipo/mongoose-rest-actions/commit/6ba006c592279f1e8405de31fdc4f0c41fc11477))

##### Tests

* **unit:**
  *  drop repetable specs ([8cc6bea3](https://github.com/lykmapipo/mongoose-rest-actions/commit/8cc6bea3dcdbdf0a4646aa2991011ae31ef09d16))
  *  refactor index specs to use test helpers ([0797d855](https://github.com/lykmapipo/mongoose-rest-actions/commit/0797d855e60364c5c9129cc4bd828541f0ee6a73))
  *  refactor get specs to use test helpers ([5ce3e39d](https://github.com/lykmapipo/mongoose-rest-actions/commit/5ce3e39dd29e0c95cb2f5bd6f2b60c1d4d109d39))
  *  refactor post specs to use test helpers ([0cbd321a](https://github.com/lykmapipo/mongoose-rest-actions/commit/0cbd321a00864d05e8f10640458dbf7ab089ecbf))
  *  refactor patch specs to use test helpers ([88f4232f](https://github.com/lykmapipo/mongoose-rest-actions/commit/88f4232f4e7c1257290bf9da699f4db66eebead7))
  *  refactor to use test helpers ([ff8e223b](https://github.com/lykmapipo/mongoose-rest-actions/commit/ff8e223bd40c147975253deb2ff90d9b5b193b00))
  *  refactor delete to use test helpers ([cc8adf7f](https://github.com/lykmapipo/mongoose-rest-actions/commit/cc8adf7fc35becea1479f5314b05143888090bd1))
  *  refactor to use test helpers ([e81f82b1](https://github.com/lykmapipo/mongoose-rest-actions/commit/e81f82b1789dffabb1df57463a15b5a6ea74fcbd))
*  refactor to use test helpers ([a55a68cd](https://github.com/lykmapipo/mongoose-rest-actions/commit/a55a68cdd2235c4ce77a3ecf3c269305845471e6))
*  improve delete test ([7c836290](https://github.com/lykmapipo/mongoose-rest-actions/commit/7c836290e6c401533eda1f651ee59f9e1bcade74))
*  refactor bootstrap to use test helpers ([57badbb4](https://github.com/lykmapipo/mongoose-rest-actions/commit/57badbb458c5320161e6bb44e6aa4cff5c57a3d0))
* **integration:**
  *  refactor & improve get and fresh specs ([c6bb9056](https://github.com/lykmapipo/mongoose-rest-actions/commit/c6bb9056b2431a74db3d87358f4cdaff002692bb))
  *  refactor & improve getById specs ([cc8cda76](https://github.com/lykmapipo/mongoose-rest-actions/commit/cc8cda762b3baf08c9e701ae0d34aa57cd8a11e0))
  *  refactor & improve put specs ([e9d91a93](https://github.com/lykmapipo/mongoose-rest-actions/commit/e9d91a930594ff453c9d1f27a2f22effb1b0d84c))
  *  improve unique error beautify specs ([a5749928](https://github.com/lykmapipo/mongoose-rest-actions/commit/a57499284b538be97c2307d8a2dfc06c97264812))
  *  refactor & improve patch spec ([55cdac32](https://github.com/lykmapipo/mongoose-rest-actions/commit/55cdac3266321162f4c1591e6014616c67743c25))
  *  ensure valid post assertions ([1bfb8991](https://github.com/lykmapipo/mongoose-rest-actions/commit/1bfb899175e20232c12f0f93a94745d379eb759e))
  *  refactor post specs ([a8c58caf](https://github.com/lykmapipo/mongoose-rest-actions/commit/a8c58caf53671afc5ad179e847923188226d1a8d))
  *  improve delete actions spec ([de7460d2](https://github.com/lykmapipo/mongoose-rest-actions/commit/de7460d2f02b7d52b8584ca12f01464b02bfd8a2))
  *  refactor delete spec to use test models ([4b6d4775](https://github.com/lykmapipo/mongoose-rest-actions/commit/4b6d47750ca3dc93887ae96f61ce4c5566a27703))

#### 0.24.1 (2019-04-16)

##### Chores

*  force latest dependencies ([970e2367](https://github.com/lykmapipo/mongoose-rest-actions/commit/970e2367a0b3654d78fafac82453aa7111c783f0))

##### Documentation Changes

*  add code of conduct and contributing guide ([a709ead2](https://github.com/lykmapipo/mongoose-rest-actions/commit/a709ead214cc4a3f0798e52207b1cea8e8d999c6))

#### 0.24.0 (2019-03-29)

##### Chores

*  merge origin/master changes ([d3a74717](https://github.com/lykmapipo/mongoose-rest-actions/commit/d3a747175e1c4235db72c401991e5ba2a36fe3e9))
*  force latest dependencies ([0d50f915](https://github.com/lykmapipo/mongoose-rest-actions/commit/0d50f9154df564c59b05fed37bab4f2b08c8ee0b))

##### New Features

*  add mongoose-aggregatable plugin ([8f5149bf](https://github.com/lykmapipo/mongoose-rest-actions/commit/8f5149bf79a7f4abbb0c687eacedc40909d96310))

##### Bug Fixes

*  resolve issue in unit tests related to sinon ([f65a0761](https://github.com/lykmapipo/mongoose-rest-actions/commit/f65a0761d037f41c50f95f7c9488fcff72f60562))

##### Refactors

*  remove console.log ([1a2e1862](https://github.com/lykmapipo/mongoose-rest-actions/commit/1a2e1862213d180f9dc8c8ac3fbfc2fe0a07fddf))
*  ensure same formatting style across editors ([763e523b](https://github.com/lykmapipo/mongoose-rest-actions/commit/763e523b3cf92622d3b2e8924c3bcf11d2c4314e))

##### Code Style Changes

*  fix a typo on code documentation ([fe647d9a](https://github.com/lykmapipo/mongoose-rest-actions/commit/fe647d9abed1debcd3ebae653864e3972f7c36d3))

#### 0.23.1 (2019-02-14)

##### Chores

*  force latest mongoose-faker ([b1070bdf](https://github.com/lykmapipo/mongoose-rest-actions/commit/b1070bdf94355825ccb99c0d1896d0109eb13d2a))

#### 0.23.0 (2019-02-13)

##### New Features

*  allow short-circuit filtered search ([4c0a0976](https://github.com/lykmapipo/mongoose-rest-actions/commit/4c0a0976399e64f83301e0c93f05f621e55657c9))

