## ハンズオン用VPC作成
|  設定項目                         | 設定値                                             | 備考                                 | 
| --------------------------------- | -------------------------------------------------- | ------------------------------------ | 
| 作成するリソース                  | VPCなど                                            |                                      | 
| 名前タグの自動生成                | 自動生成✅、cloudtech                              |                                      | 
| IPv4 CIDRブロック                 | 10.0.0.0/16                                        | デフォルト値のまま                   | 
| IPv6 CIDR ブロック                | IPv6 CIDR ブロックなし✅                           | デフォルト値のまま                   | 
| テナンシー                        | デフォルト　                                       | デフォルト値のまま                   | 
| アベイラビリティゾーン (AZ) の数  | 1                                                  |                                      | 
| パブリックサブネットの数          | 1                                                  |                                      | 
| プライベートサブネットの数        | 1                                                  |                                      | 
| NAT ゲートウェイ ($)              | 1AZ 内                                             |                                      | 
| VPC エンドポイント                | なし                                               | NATゲートウェイを置くので不要        | 
| DNS オプション                    | DNS ホスト名を有効化✅　<br>DNS 解決を有効化✅     | デフォルト値                         | 
| 追加のタグ                        | 新しいタグを追加　<br>キー：Purpose、値：cloudtech | 最後に消す対象がわかるようにするため | 