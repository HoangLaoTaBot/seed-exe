# Hướng dẫn cấu hình file config.json
| TỪ KHÓA   | GIÁ TRỊ                              | Ý NGHĨA                                                                    |
|-----------|--------------------------------------|----------------------------------------------------------------------------|
| AUTO_SPIN | true / false                         | ( On / Off ) Tính năng tự động quay spin                                   |
| AUTO_BIRD | true / false                         | ( On / Off ) Tính năng tự động cho chim ăn và đi săn                       |
| AUTO_TASK | true / false                         | ( On / Off ) Tính năng tự động làm nhiệm vụ                                |
| AUTO_MERGE_PIECE_EGG | true / false                         | ( On / Off ) Tính năng tự động ghép trứng                                  |
| VALUE_MIN_MERGE_PIECE_EGG | 36                                   | Phí ghép trứng tối thiểu, vượt quá sẽ không ghép                           |
| AUTO_TRANSFER_EGG | true / false                         | ( On / Off ) Tính năng tự động chuyển trứng                                |
| VALUE_ID_TRANSFER_EGG | 933814601                            | ID của người nhận                                                          |
| AUTO_JOIN_GUILD | true / false                         | ( On / Off ) Tính năng tự động join guild                                  |
| VALUE_ID_GUILD | 6c8bd846-0582-4832-8531-4d5a785a84da | ID của Guild                                                               |
| AUTO_BOOST | true / false                         | ( On / Off ) Tính năng tự động nâng cấp                                    |
| VALUE_UPGRADE_MINING_SPEED | 6                                    | Level nâng cấp Tree                                                        |
| VALUE_UPGRADE_STORAGE_SIZE | 2                                    | Level nâng cấp Storage                                                     |
| AUTO_WRITE_ERROR | true / false | ( On / Off ) Tính năng ghi log lỗi ra file error.txt                                    |
| AUTO_SEND_ERROR_TELEGRAM | true / false | ( On / Off ) Tính năng gửi thông báo lỗi sang telegram channel                          |
| USER_AGENT |  | User agent fake thông tin thiết bị                                                      |
| AUTO_STOP_PROCESS | true / false | ( On / Off ) Tính năng tự động dừng script khi call API lỗi quá 10 lần                  |
| IS_CHECK_QUERY_ID | true / false | ( On / Off ) Tính năng kiểm tra query_id còn hạn không                                  |
| NUMBER_TRY_REQUEST | 3            | Số lần thử call lại API khi lỗi                                                         |
| THREAD | 10           | Số luồng chạy đồng thời cùng lúc                                                        |
| IS_SLEEP | 27500        | Số thời gian đợi chạy vòng lặp mới ( giây )                                             |
| BOT_TOKEN |              | Token của bot telegram channel                                                          |
| BOT_CHANNEL_ID |              | ID của telegram channel                                                                 |
| BOT_NAME_GAME | SEED                                  | Tên game                                                                   |
