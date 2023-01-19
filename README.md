# Simple-Calculator-OOP

    def divide(self):
        number = self.label.text()
        self.label.setText(number + "/")

    def back(self):

        number = self.label.text()
        number = number[1:]
        self.label.setText(number)

    def AC(self):

        self.label.setText("")
