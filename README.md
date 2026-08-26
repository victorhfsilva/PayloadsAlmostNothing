# Payloads Almost Nothing

Coleção de wordlists voltada para testes de segurança em aplicações web, organizada por stack tecnológica, categoria de recursos e classes de vulnerabilidade. Cada arquivo contém uma entrada por linha, pronta para uso direto em ferramentas de fuzzing e no Burp Suite (Intruder, Automate, etc.).

## Uso

Exemplos com ferramentas comuns:

```bash
# ffuf
ffuf -u https://alvo.com/FUZZ -w wordlist.txt -mc 200,301,302,401,403

# gobuster
gobuster dir -u https://alvo.com -w wordlist.txt

# feroxbuster
feroxbuster -u https://alvo.com -w wordlist.txt

```

No Burp Suite, as wordlists podem ser carregadas diretamente no Intruder (Payloads → Load) ou usadas no Automate como payload source.

## Licença

Uso livre para fins de segurança ofensiva e defensiva. Utilize por sua conta e risco.
