@@ -0,0 +1,27 @@
{
    " versão " : " 0.2.0 " ,
    " configurações " : [
        {
            //  Use  IntelliSense  para  encontrar  para fora  que  os atributos  existem  em  C #  depuração
            //  Use  pairar  para  a  descrição  dos existentes atributos   
            //  Para obter  mais  informações,  visite  https : //github.com/OmniSharp/omnisharp-vscode/blob/master/debugger-launchjson.md
            " name " :  " .NET Core Launch (console) " ,
            " tipo " : " coreclr " ,
            " request " : " launch " ,
            " preLaunchTask " : " build " ,
            //  Se  você  tiver  mudado  alvo  frameworks,  fazer  a certeza  de  atualizar  o  programa de  caminho.
            " program " : " $ {workspaceFolder} /bin/Debug/net5.0/Series.dll " ,
            " args " : [],
            " cwd " : " $ {workspaceFolder} " ,
            //  Para obter  mais  informações  sobre  o  campo 'console'  ,  consulte  https : //aka.ms/VSCode-CS-LaunchJson-Console
            " console " :  " internalConsole " ,
            " stopAtEntry " : falso
        },
        {
            " name " : " .NET Core Attach " ,
            " tipo " : " coreclr " ,
            " request " : " attach " ,
            " processId " : " $ {command: pickProcess} "
        }
    ]
} 
