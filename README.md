# WebApplication1

先打開 SQL Server Management Studio (SSMS)。這時候會跳出登入視窗，
請直接看 「Server name (伺服器名稱)」 欄位欄位寫什麼：
如果上面預設寫 .、(local) 或 localhost $\rightarrow$ 你的連線字串就寫 Server=.。
如果上面寫 電腦名稱\SQLEXPRESS $\rightarrow$ 你的連線字串就寫 Server=電腦名稱\\SQLEXPRESS。
上機考不怎麼用 LocalDB（因為 LocalDB 是微軟附贈給開發者在本機輕量測試用的，不適合當作大型標準上機考的正式環境），
所以幾乎不出現 (localdb)\MSSQLLocalDB。
