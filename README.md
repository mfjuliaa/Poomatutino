# Poomatutino

return (
            <>  
                <h1> Calcula o imc </h1>

                <form>
                    <div>
                        <label>
                            <span>peso</span><br />
                            <input ref={pesoRef} onChange={handleChange} type="number" />
                        </label>
                    </div>
                    <div>
                        <label>
                            <span>Altura</span> <br />
                            <input ref={AlturaRef} onChange={handleChange} type="number" />
                        </label>
                    </div>
                    <div> ref={resultadoRef}</div>
                </form>
            </>
        )
