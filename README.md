```python
#region A bit of me (💙)
class GustavoRosasDev:
    def __init__(self):
        self.name = "Gustavo Rosas"
        self.description = "Bem-vindo ao meu perfil do GitHub! Eu me chamo Gustavo Rosas, sou um desenvolvedor multidisciplinar com experiência em diversas tecnologias. Adoro explorar novas linguagens de programação e frameworks, e estou sempre animado para trabalhar em projetos desafiadores."
        self.current_skills = [
            "Python", "C#", "Flutter", "Dart", "HTML", "CSS", "JavaScript", "React", "Firebase", "Stripe"
        ]
        self.gui_frameworks = [
            "PySimpleGUI", "CustomTkinter"
        ]
        self.api_usage = [
            "REST APIs", "Firebase", "Stripe"
        ]
        self.version_control = [
            "Git", "GitHub"
        ]
        self.other_skills = [
            "Adobe (Illustrator, Photoshop e Premiere)", "SketchUp", "Unity"
        ]
        self.projects = [
            {
                "name": "DocBuilder",
                "description": "O DocBuilder é um aplicativo desktop simples, porém poderoso para arquitetos e engenheiros, feito em python e conectado com algumas APIs (Consultar CEP, Consultar CNPJ, etc), que automatizam todo o processo de preenchimento dos documentos. (em andamento)"
            },
            {
                "name": "Journalist Assistant",
                "description": "O Journalist Assistant é um aplicativo desktop simples porém poderoso, que integra as API's do Google Sheets e Google Drive e tem como principal objetivo automatizar o processo de extrair dados do sheets (1), pesquisar no drive (2), gerar um link de compartilhamento publico (3) e atualizar a célula (com nome correspondente) do Google Sheets com o hyperlink do arquivo localizado no Google Drive (4)."
            }
        ]

    def contact_information(self):
        return {
            "email": "python.dev.br@gmail.com",
            "whatsapp": "+55 11 9 6659-3807"
        }


def main():
    # Usage
    dev = GustavoRosasDev()

    # Print information
    print("Sobre Mim:")
    print(dev.description, '\n')

    print("Habilidades atuais em programação:")
    print("Linguagens:")
    for language in dev.current_skills:
        print(language, '\n')

    print("Frameworks para criação de Interfaces Gráficas (GUI):")
    for framework in dev.gui_frameworks:
        print(framework, '\n')

    print("Consumo de API's (criação, em breve):")
    for api in dev.api_usage:
        print(api, '\n')

    print("Versionamento de software:")
    for tool in dev.version_control:
        print(tool, '\n')

    print("Outras Habilidades:")
    for skill in dev.other_skills:
        print(skill, '\n')

    print("Projetos (seção em construção):")
    for project in dev.projects:
        print("Nome:", project["name"])
        print("Descrição:", project["description"], '\n')

    print("Entre em Contato:")
    contact = dev.contact_information()
    print("Email:", contact["email"])
    print("WhatsApp:", contact["whatsapp"])


if __name__ == "__main__":
    main()
#endregion
```
