# xiaoxue
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>表单</title>
</head>
<body>
    <form action="https://raink.net/api/html/save"  target="_self">
        <fieldset>
            <legend>基本信息</legend>
            <h4>1. 你的名字</h4>
            <input type="text">
            <h4>2.你的手机号</h4>
            <input type="text" value="137******2473" readonly>
            <h4>3.你的性别</h4>
            <input type="radio" name="gender" >男
            <input type="radio" name="gender" >女
            <input type="radio" name="gender"  disabled>保密
            <h4>4.家庭地址</h4>
            <select name="" id="">
                <option value="">---哪一个省/直辖市---</option>
            </select><select name="" id="">
                <option value="">---市/区---</option>
            </select><select name="" id="">
                <option value="">---县----</option>
            </select><select name="" id="">
                <option value="">---乡---</option>
            </select>
            <br>
            <br>
            <textarea name="" id="" cols="65" rows="4"></textarea>
            <h4>你现在的身体状况</h4>
            <input type="checkbox">健康
            <br>
            <input type="checkbox">发热
            <br>
            <input type="checkbox">干咳
            <br>
            <input type="checkbox">乏力
            <br>
            <input type="checkbox">呼吸困难
            <br>
            <input type="checkbox">咽痛
            <br>
            <input type="checkbox">胸痛
            <br>
            <h4>6.你的健康码的颜色</h4>
            <input type="radio" name="color" >绿色
            <input type="radio" name="color" >黄色
            <input type="radio" name="color" >红色
            <h4>7.你是否在14天内有过中高风险地区,或跟确诊人员有过密切接触</h4>
            <input type="radio" name="color" >是
            <input type="radio" name="color" >否
            <h4>8.疫苗接种情况</h4>
            <input type="radio" name="vaccines" >以接种第一针
            <input type="radio" name="vaccines" >以接种第二针
            <input type="radio" name="vaccines" >以接种第三针
        </fieldset>
        <fieldset>
            <legend>保密信息</legend>
            <h4>1.身份证信息</h4>
            正面：<input type="file">
            <br>
            <br>
            反面：<input type="file">
            <br>
            <br>
            <h4>2.学历信息(最高)</h4>
            <select name="" id="">
                <option value="">研究生</option>
                <option value="">本科</option>
                <option value="">大专</option>
                <option value="">高中</option>
                <option value="">其他</option>
            </select>
            <h4>3.是否服兵役</h4>
            <input type="radio" name="ismilitary"  id="yes">
            <label for="yes">是</label>
            <input type="radio" name="ismilitary"  id="no">
            <label for="no">否</label>
            <h4>4.个人意见</h4>
            <textarea name="" id="" cols="30" rows="10"></textarea>
        </fieldset>
        <input type="submit" value="上传信息">
        <input type="reset" value="清空信息">
    </form>
    
</body>
</html>
