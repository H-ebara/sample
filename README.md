# CRANEのプログラムのチェックリスト

## 起動方法
2つのターミナルでそれぞれ起動
1. `roscore`
2. `roslaunch crane_x7_bringup demo.launch fake_execution:=false`

※ロボットが動かない場合は，`sudo chmod 666 /dev/ttyUSB0`を実行する

## チェックリスト
- [ ] 上記の2プログラムは起動しているか？
- [ ] 非常停止ボタンが押されたままになっていないか？
- [ ] 非常停止ボタンとPC がきちんとUSBケーブルで繋がれているか？
- [ ] rosbagでエラーは表示されていないか？
