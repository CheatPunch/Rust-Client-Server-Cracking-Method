# Cracking the server
1. Download Rust dedicated server files
2. Navigate to RustDedicated_Data\Managed
3. Drag n' Drop your Assembly-CSharp.dll into a .NET decompiler (dnSpy, etc)
4. Open namespace 'Rust'
5. Open class 'Defines'
6. Edit 'Defines' class and change the appID to '480u'

It should look like this, after it's done:

		public static uint appID = 480u;
    
    
    
    
    
# Cracking the client

1. Download Rust (client files)
2. Navigate to RustClient_Data\Managed
3. Drag n' Drop your Assembly-CSharp.dll into a .NET decompiler (dnSpy, etc)
4. Open namespace 'Rust'
5. Open class 'Defines'
6. Edit 'Defines' class and change the appID to '480u'

It should look like this, after it's done:

		public static uint appID = 480u;
