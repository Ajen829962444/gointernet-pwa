export default function Home() {
  return (
    <main className="flex min-h-screen flex-col items-center justify-center bg-white text-gray-900 p-4">
      <div className="w-full max-w-md text-center space-y-6 border-2 border-blue-500 rounded-2xl p-6 shadow-xl">
        <img
          src="/logo.png"
          alt="Go Internet Logo"
          className="mx-auto w-24 h-24 rounded-full shadow-md"
        />
        <h1 className="text-3xl font-bold text-blue-600">Go Internet</h1>
        <p className="text-lg text-gray-700">
          Status: <span className="text-green-500 font-semibold">Conectado</span>
        </p>
        <button className="bg-blue-600 hover:bg-blue-700 text-white font-bold py-2 px-6 rounded-full transition">
          Desconectar
        </button>
        <p className="text-sm text-gray-500">
          Conectado com segurança via VPN • IP: 192.168.0.1
        </p>
      </div>
    </main>
  );
}
