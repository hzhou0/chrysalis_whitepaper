## Attack Vectors

| Method                    | Description                                                  | Defense                                                      | Risk   |
| ------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------ |
| 51% Attack                | The attacker attempts to gain over 51% of the votes in the network. | The mint always has full authority on the state of the currency. | None   |
| Sybil Attack              | The attacker creates many nodes on the network to try to influence consensus | Same as above.                                               | None   |
| DDoS                      | The attacker floods the network with a large amount of traffic. | The requests nodes are blocked from sending excessive data due to the dynamic difficulty on proof of work. The auditors will be restricted to sending lists only once per block during voting. | Medium |
| Faking Malicious Behavior | The attacker creates a group of auditors which falsely proves the mint acted maliciously. | There must be network consensus on the input candidate lists before the output state is broadcasted. This likely requires some kind of co-signing mechanism. | Low    |

