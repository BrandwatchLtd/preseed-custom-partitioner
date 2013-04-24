# preseed-custom-partitioner

An example custom hook for debian-installer that will let you run your own logic for partitioning, LVM, and software RAID when bootstrapping a machine.

## Requirements

1. An existing Debian/Ubuntu preseed setup.
2. Working DHCP/TFTP/PXE boot capability (not strictly required, but typically necessary)

## Quick start

1. Add the contents of preseed.cfg to your existing preseed configuration.
2. Copy lvm.sh to the root directory of your preseed source server.
3. Boot a machine using preseed!


## Copyright and License

Copyright 2013 Socrata, Inc.

Licensed under the Apache License, Version 2.0 (the "License"); you may you may not use this work except in compliance with the License. You may obtain a copy of the License in the LICENSE file, or at:

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
