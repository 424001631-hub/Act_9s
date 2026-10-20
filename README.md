# Act_9s

class Gregg {
  String _color;

  Gregg(this._color);

  String get color => _color;

  void shout() {
    if (_color.toLowerCase() == "green") {
      print("Gregg ($_color): I'll be the best jungler");
    } else if (_color.toLowerCase() == "yellow") {
      print("Gregg ($_color): I like Java Chip, 10/10 sha");
    } else if (_color.toLowerCase() == "red") {
      print("Gregg ($_color): I will crush them all!");
    }
  }
}

void main() {
  final squad = [Gregg("Green"), Gregg("Yellow"), Gregg("Red")];

  for (final gregg in squad) {
    gregg.shout();
  }
}
