class Attributes(r8st):
    @staticmethod
    def channels() -> str:
        """
        Returns the Discord channel for professional communication.

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
