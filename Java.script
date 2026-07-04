function check() {
  let url = document.getElementById("urlInput").value;
  let result = document.getElementById("result");

  if (!url) {
    result.innerHTML = "Aucun lien";
    return;
  }

  if (url.includes("login") || url.includes("verify")) {
    result.innerHTML = "🔴 Suspect";
  } else {
    result.innerHTML = "🟢 OK";
  }
}
