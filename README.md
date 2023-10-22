+------------------------------------+
|               iPhone              |
+------------------------------------+
| - numeroTelefone: String          |
| - musicas: List<Musica>           |
| - navegador: NavegadorInternet    |
+------------------------------------+
| + fazerLigacao(destino: String)   |
| + enviarMensagem(destino: String, mensagem: String) |
| + tocarMusica()                   |
| + pararMusica()                   |
| + abrirSite(url: String)          |
+------------------------------------+
| + iPhone()                        |
+------------------------------------+

+-----------------------+
|        Aparelho Telefônico         |
+-----------------------+
| + fazerLigacao(destino: String)   |
| + enviarMensagem(destino: String, mensagem: String) |
+-----------------------+

+------------------------+
|    Reprodutor Musical     |
+------------------------+
| - musicas: List<Musica>           |
+------------------------+
| + tocarMusica()                   |
| + pararMusica()                   |
+------------------------+

+---------------------------------+
|   Navegador na Internet   |
+---------------------------------+
| + abrirSite(url: String)          |
+---------------------------------+

+--------------+
|   Musica   |
+--------------+
| - titulo: String                  |
| - artista: String                 |
+--------------+
