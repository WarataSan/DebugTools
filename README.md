# DebugTools

機能：
- InGame Console
 ゲーム中にログやDIPのデータ変更を行えます
 
![image](https://user-images.githubusercontent.com/91827267/142227024-fccbcefa-8337-4bbc-85a1-b897565f829d.png)

> ---DIP コンソール操作例---
> 
> `dip GameSystem:GameSpeed 30`
> 
> ---コンソール設定画面表示方法---
> `Edit->ProjectSettings->DebugTool->Settings`
> 
> ![image](https://user-images.githubusercontent.com/91827267/142964896-c1903935-51cb-4f75-a5c0-6d849fc58f3e.png)
> 
> 
> Enable Console:コンソールをゲーム内で使用する
> Console Command:コンソール表示に使用するキーコマンド
> IsInclude Log:通常のログをコンソールに含める ('DebugTool.Trace' こちらの関数はコンソールに含まれる)
> MaxLogNum:コンソールに含めるログの最大数
> 
> ![image](https://user-images.githubusercontent.com/91827267/142965363-d7e05adb-43fa-423e-a281-5314ba37b8f2.png)
> 

- Dip Switch
 デバッグ用のスイッチデータを作成できます
 値に合わせて、好みのデバッグ処理を行うことが可能
 
![image](https://user-images.githubusercontent.com/91827267/142227083-1b63f961-558c-4bdb-a152-d7b7d2600114.png)

> ---DIP Script操作例---
> <DIPの設定>
> 
> `dev.DIP.SetValue<int>(dev.DIP.GameSystem.ID.GameSpeed, GameFPS);`
> <DIPの取得>
> 
> `var gameSpeed = dev.DIP.GetValue<int>(dipID);`
> 
> ---DIP設定画面表示方法---
> DebugTool->DipTool
> 
> ![image](https://user-images.githubusercontent.com/91827267/142964754-fb6d16ce-e2ec-434a-a8de-9332defb4275.png)
> 
