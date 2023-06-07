
/*
#![feature(proc_macro_hygiene, decl_macro)]

#[macro_use]
extern crate rocket;
extern crate rocket_contrib;

use rocket_contrib::json::JsonValue;

#[get("/hello/<id>")]
fn hello(id: usize) -> JsonValue {
    let response = json!({
        "message": "Received ID: ",
        "id": id
    });
    response.into()
}

fn main() {
    rocket::ignite().mount("/", routes![hello]).launch();
}

*/