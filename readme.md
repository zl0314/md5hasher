详细方法：

$hasher = new Md5Hasher;
$result = $hasher->make('zl');
echo $result; //输出加密结果
echo $hasher->check('zl','c28cbd398a61e9022fd6a6835a57dc50'); //检查是否一致
