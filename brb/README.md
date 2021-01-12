# BRB: Byzantine Reliable Broadcast

[MaidSafe website](http://maidsafe.net) | [Safe Network Forum](https://safenetforum.org/)
:-------------------------------------: | :---------------------------------------------:

## About

This crate provides a deterministic implementation of Byzantine Reliable Broadcast (BRB) with dynamic membership.

For an overview how BRB works, please see these [slides](https://docs.google.com/presentation/d/1AZrauwhTYyNz89zQw_cFa9hkqpS6HPkPzNw3Q7Fkscw/edit?usp=sharing).

This crate and its related crates (`brb_*`) implement a loosely-coupled Byzantine Fault Tolerant (BFT) system for achieving network agreement over eventually consistent data-type algorithms.

## Traits

trait | description
----- | -----------
|[BRBDataType](src/brb_data_type.rs)| Data types to be secured should implement this|

## Prior Work

This crate and its sibling have been broken out of the original [bft-crdts](https://github.com/davidrusu/bft-crdts/) crate.  Additional documentation and source code can be found there.


## License

This Safe Network software is dual-licensed under the Modified BSD (<LICENSE-BSD> <https://opensource.org/licenses/BSD-3-Clause>) or the MIT license (<LICENSE-MIT> <https://opensource.org/licenses/MIT>) at your option.

## Contributing

Want to contribute? Great :tada:

There are many ways to give back to the project, whether it be writing new code, fixing bugs, or just reporting errors. All forms of contributions are encouraged!

For instructions on how to contribute, see our [Guide to contributing](https://github.com/maidsafe/QA/blob/master/CONTRIBUTING.md).
