fn main() {
    let developer = ("YourName", "Rustacean 🦀"); // Tuple struct pattern
    
    println!("━━━━ � 𝙍 𝙊 𝙁 𝙄 𝙇 𝙀 ━━━━");
    println!("✦ Name: {}", developer.0);
    println!("✦ Focus: {}", "Systems Programming"); 
    println!("✦ Mantra: {:?}", "Fast. Safe. Concurrent.");
    
    let socials = vec![
        ("GitHub", "@yourusername"),
        ("Twitter", "@yourhandle")
    ];

    println!("\n🔗 Connect:");
    socials.iter().for_each(|(platform, handle)| {
        println!("• {}: {}", platform.cyan().bold(), handle);
    });

    println!("\n⚡ Fun fact: Can recite Rust's ownership rules in sleep!");
}
