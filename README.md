fn main() {
    let greetings = "👋 Greetings!";
    let age = 15;
    let school = "high school student";
    let passion = "fervor for data science, software, and video game development";
    let location = "Residing in Germany";
    let techLove = "huge fan of Arch Linux";
    let pursuit = "aligning pursuits with the precision and sophistication characteristic of the tech landscape";
    let emoticon = ":3";

    let bio = format!(
        "{}\nI am a {}-year-old {} with a {}.\n{}\n{}\n{}",
        greetings, age, school, passion, location, techLove, pursuit
    );

    println!("{}", bio);
}
