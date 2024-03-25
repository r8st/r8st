[![MasterHead](https://cdn.discordapp.com/attachments/1203763906657394688/1221849023242047769/r8st.png?ex=66141293&is=66019d93&hm=1f466f7fe162f1e217a9acc4af3e1806b80c44913fe91c244d0f0e055fb8e3c6&)


    :return: Discord channel link
    """
    discord = "discord.gg/has1mrp"
    return discord

@staticmethod
def contact() -> str:
    """
    Returns the preferred contact handle for professional inquiries.

    :return: Discord handle
    """
    discord = "r8st"
    return discord

@staticmethod
def life() -> tuple:
    """
    Returns information about language proficiency and age.

    :return: Tuple containing languages and age
    """
    langs = ['Turkish', 'English']
    age = 16
    return langs, age

@staticmethod
def coding() -> tuple:
    """
    Returns information about coding expertise, specialties, and development environment.

    :return: Tuple containing languages, specialties, and development environment
    """
    langs = {
        'expert': ['Node'],
        'intermediate': ['js', 'c#'],
        'learning': ['golang']
    }
    specialities = ['web/app reverse engineering', 'fullstack']
    environnement = ['vscode']
    return langs, specialities, environnement
