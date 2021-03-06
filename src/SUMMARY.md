<!--
  -- Copyright (c) 2019, Arm Limited, All Rights Reserved
  -- SPDX-License-Identifier: Apache-2.0
  --
  -- Licensed under the Apache License, Version 2.0 (the "License"); you may
  -- not use this file except in compliance with the License.
  -- You may obtain a copy of the License at
  --
  -- http://www.apache.org/licenses/LICENSE-2.0
  --
  -- Unless required by applicable law or agreed to in writing, software
  -- distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
  -- WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
  -- See the License for the specific language governing permissions and
  -- limitations under the License.
--->

# Summary

- [Introduction](README.md)
- [Platform Abstraction for Security](parsec/README.md)
    - [Operations](parsec/operations/README.md)
        - [AddClient](parsec/operations/add_client.md)
        - [ListOpcodes](parsec/operations/list_opcodes.md)
        - [ListProviders](parsec/operations/list_providers.md)
        - [Ping](parsec/operations/ping.md)
        - [ProveClient](parsec/operations/prove_client.md)
        - [PsaAsymmetricSign](parsec/operations/psa_asymmetric_sign.md)
        - [PsaAsymmetricVerify](parsec/operations/psa_asymmetric_verify.md)
        - [PsaCreateKey](parsec/operations/psa_create_key.md)
        - [PsaDestroyKey](parsec/operations/psa_destroy_key.md)
        - [PsaExportPublicKey](parsec/operations/psa_export_public_key.md)
        - [PsaImportKey](parsec/operations/psa_import_key.md)
        - [ShareTrustBundle](parsec/operations/share_trust_bundle.md)
        - [Key Attributes](parsec/operations/key_attributes.md)
    - [Providers](parsec/providers.md)
    - [API Overview](parsec/api_overview.md)
    - [Interfaces and Dataflow](parsec/interfaces_and_dataflow.md)
    - [Source Code Structure](parsec/source_code_structure.md)
    - [Status Codes](parsec/status_codes.md)
    - [System Architecture](parsec/system_architecture.md)
    - [Wire Protocol](parsec/wire_protocol.md)
- [User guides](user_guides/README.md)
    - [How to install Parsec on Linux](user_guides/install_parsec_linux.md)
    - [Parsec Configuration](user_guides/configuration.md)
    - [How to use Parsec](user_guides/use_parsec.md)
- [Developer guides](dev_guides/README.md)
    - [How to build Parsec](dev_guides/build.md)
    - [How to test Parsec](dev_guides/test.md)
    - [Writing a new Parsec Client Library](dev_guides/writing_library.md)
    - [Adding a new Parsec Provider](dev_guides/adding_provider.md)
